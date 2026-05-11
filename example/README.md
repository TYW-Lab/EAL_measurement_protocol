# Multiphoton Attenuation Length Measurement

This repository provides a pipeline for measuring the **effective attenuation length (EAL)** of tissue phantoms. The workflow is designed to be compatible with **Bruker multiphoton systems** and includes both data acquisition guidelines and analysis methods.

---

## Overview

The goal of this project is to estimate the effective attenuation length (EAL) by analyzing fluorescence signals acquired at different imaging depths and excitation powers. The method ensures that only non-saturated two-photon signals are used for accurate estimation.

---
## Experimental Procedure

### 1. Background Acquisition
- Acquire a background image with:
  - Laser **turned off**
  - PMT **operating normally**

### 2. Z-stack Acquisition
- Scan the same volume using a series of different excitation powers.
- Use a **step size of 10 µm** between imaging planes.

---

## Data Processing Pipeline
The main notebook is organized into:
- Imports
- Utility Functions
- Load Data
- Background Subtraction
- Determination of the Power Range for Unsaturated 2PE for Each Depth
- Selection of the Depth Range for EAL Calculation
- EAL Estimation

The analysis workflow is:

### 1. Background Subtraction
All images are corrected by subtracting the averaged background stack.

- Negative values after subtraction are clipped to zero.
- The fluorescence signal at each depth is defined as the mean intensity of the brightest `TOP_PERCENT` percent of pixels.
- In the current notebook, this threshold is controlled by `TOP_PERCENT`.

---

### 2. Determination of the Power Range for Unsaturated 2PE for Each Depth

For each imaging depth:
- Extract fluorescence signals under different excitation powers.
- Convert EOM values to excitation power using `lookuptable.xlsx`.
- Perform **linear fits in log-log space**:

`log(Signal) = k log(Power) + b`

- The expected slope for ideal two-photon excitation is **~2**.

This step is used to:
- Identify the contiguous **power range** where the signal is not saturated.
- Exclude powers that deviate from two-photon behavior.
- Select the window with slope closest to `TARGET_TWO_PHOTON_SLOPE = 2.0`.
- Candidate fitting windows use at least `MIN_FIT_POINTS` points. When `MAX_FIT_POINTS = None`, the maximum window length is `N - 1`, matching the current notebook logic.

---

### 3. Selection of the Depth Range for EAL Calculation

- Save the per-depth best slope, best EOM, and power to:
  - `depth_analysis_topPercent.xlsx`
- Plot the best fitted slope as a function of depth:
  - `depth_vs_slope.png`
- Select the zero-based stack index range used for EAL fitting with:
  - `Z_MIN_IDX`
  - `Z_MAX_IDX`
  - `DEPTH_STEP_UM`

---

### 4. EAL Estimation

- For each selected depth, use the power point just below the best unsaturated upper EOM.
- Compute:

`y = log(S / P²)`

where:
  - `S` is the fluorescence signal
  - `P` is the excitation power

- Perform a **linear fit** between:
  - Imaging depth
  - `log(S / P²)`

- Obtain the fitted slope `k`

- Compute EAL using: `EAL = -2/k`
- Save the final fit plot to:
  - `EAL.png`

---

## Important Notes

### 1. Fluorescence Signal Definition
- The fluorescence signal at each depth is defined as:
  - The **mean intensity of the brightest `TOP_PERCENT` percent of pixels**
- This threshold is a **tunable parameter**.

---

### 2. Two-Photon Validation

- The code generates:
  - `depth_vs_slope.png`

This plot shows the fitted slope (signal vs. power) at each depth.

**Best practice:**
- Only include depths where the slope is **close to 2** when calculating EAL.
- This ensures the signal remains within the **true two-photon excitation regime**.
- The current notebook uses `Z_MIN_IDX`, `Z_MAX_IDX`, and `DEPTH_STEP_UM` to define the depth range for EAL estimation.

---

## Files in This Repository

- `2P_EAL.ipynb` — Main analysis notebook 
- `depth_analysis_topPercent.xlsx` — Intermediate processed data  
- `depth_vs_slope.png` — Power-law validation across depths  
- `EAL.png` — Final EAL fitting result  
- `ZSeries-*` — Raw imaging datasets
- `lookuptable.xlsx` — EOM vs Power
- `bg/` — Background image dataset

---

## Summary

This pipeline provides:
- A robust method to avoid **two-photon saturation artifacts**
- A reproducible way to compute **effective attenuation length**
- Compatibility with **Bruker imaging systems**
