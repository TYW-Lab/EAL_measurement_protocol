# Effective attenuation length (EAL) measurement protocol

## Materials:

Instead of just using links, list the product part number, such as Sigma Aldrich, A4018-5G. One can also put a hyperlink to it, but with these part numbers, even if a link expires, people can still find out what it is.

- [Agarose](https://www.sigmaaldrich.com/US/en/product/sial/a4018)
- [1um fluorescent beads](https://www.thermofisher.com/order/catalog/product/F13081?SID=srch-srp-F13081): $C_{fluo} = 1\times10^{7}\ \text{beads}/\text{µL}$
- [1um non-fluorescent polystyrene beads](https://polysciences.com/products/polybead-microspheres-100181m?srsltid=AfmBOorjVsqH1_RPydiDL_rl2QxODNqYwh8yssEixcAhqj7QJ9CAVFyL): $C_{poly} = 4.55\times10^{7}\ \text{beads}/\text{µL}$

---

## Dilution calculation

1. Take 1 g of agarose per 100 mL of water as the base medium.
2. The tissue phantom is prepared by mixing:

- Fluorescent beads: $V_{fluo} = 4\ \text{µL}$
- Non-fluorescent polystyrene beads: $V_{poly} = 40\ \text{µL}$
- Agarose solution: $V_{ag} = 156\ \text{µL}$

1. The concentration of fluorescent beads:

$$
\frac{C_{fluo} \times V_{fluo}}{V_{fluo} + V_{poly} + V_{ag}}
= \frac{(1 \times 10^{7}\ \text{beads}/\text{µL}) \times (4\ \text{µL})}{(4 + 40 + 156)\ \text{µL}}
= 2 \times 10^{5}\ \text{beads}/\text{µL}
$$

1. The concentration of non-fluorescent polystyrene beads:

$$
\frac{C_{poly} \times V_{poly}}{V_{fluo} + V_{poly} + V_{ag}}
= \frac{(4.55 \times 10^{7}\ \text{beads}/\text{µL}) \times (40\ \text{µL})}{(4 + 40 + 156)\ \text{µL}}
= 9.1 \times 10^{6}\ \text{beads}/\text{µL}
$$

1. Ratio between non-fluorescent polystyrene beads and fluorescent beads:

$$
R = \frac{9.1 \times 10^{6}\ \text{beads}/\text{µL}}{2 \times 10^{5}\ \text{beads}/\text{µL}} = 45.5 : 1
$$

---

## Equipment and Supplies

![Sample preparation setup](images/sample_preparation.png)

1. <a id="eq-scale"></a>Scale (What is the precision requirement?)
2. <a id="eq-bottle"></a>Heat resistant bottle for mixing and storing agarose solution
3. <a id="eq-hotplate"></a>Stirring hotplate (e.g., Cimarec, or other more permanent vendors?)
4. <a id="eq-tubes"></a>Microcentrifuge tubes
5. <a id="eq-rack"></a>Tube rack
6. <a id="eq-pipettes"></a>Pipettes (2–20 µL and 20–200 µL, kept in a pipette stand)

*Position 7 (sharps container) is not used in this protocol.*

8. <a id="eq-vortexer"></a>Vortexer ([https://www.sigmaaldrich.com/US/en/product/aldrich/z258423?utm_source=google&utm_medium=cpc&utm_campaign=23331190685&utm_content=194830326172&gad_source=1&gad_campaignid=23331190685&gbraid=0AAAAAD8kLQSS_6w2_B1C1Bi5Sa_Ktb4WU&gclid=CjwKCAjwtvvPBhBuEiwAPMijrzI-B3EqGSsYTCZIccVJ85d4c7gr-BJnYrwrmTU8NBiiDqytkhDM7hoCxJQQAvD_BwE](https://www.sigmaaldrich.com/US/en/product/aldrich/z258423?utm_source=google&utm_medium=cpc&utm_campaign=23331190685&utm_content=194830326172&gad_source=1&gad_campaignid=23331190685&gbraid=0AAAAAD8kLQSS_6w2_B1C1Bi5Sa_Ktb4WU&gclid=CjwKCAjwtvvPBhBuEiwAPMijrzI-B3EqGSsYTCZIccVJ85d4c7gr-BJnYrwrmTU8NBiiDqytkhDM7hoCxJQQAvD_BwE)) (Fix it according to the format we discussed.)

**Additional items not labeled in the figure**

- <a id="eq-beaker"></a>Beaker (used as a water bath around the agarose container)
- <a id="eq-stirbar"></a>Magnetic stir bar (e.g., vendor: [[https://www.sigmaaldrich.com/US/en/product/aldrich/z282456?utm_source=google&utm_medium=cpc&utm_campaign=23331190685&utm_content=194830326172&gad_source=1&gad_campaignid=23331190685&gbraid=0AAAAAD8kLQSS_6w2_B1C1Bi5Sa_Ktb4WU&gclid=CjwKCAjwtvvPBhBuEiwAPMijr_WbPgAh6LRYkxQCAvRytWpy8d6M3-D5_5JFgzTYt44BOdLEZkLuKhoCHpMQAvD_BwE]](https://www.sigmaaldrich.com/US/en/product/aldrich/z282456?utm_source=google&utm_medium=cpc&utm_campaign=23331190685&utm_content=194830326172&gad_source=1&gad_campaignid=23331190685&gbraid=0AAAAAD8kLQSS_6w2_B1C1Bi5Sa_Ktb4WU&gclid=CjwKCAjwtvvPBhBuEiwAPMijr_WbPgAh6LRYkxQCAvRytWpy8d6M3-D5_5JFgzTYt44BOdLEZkLuKhoCHpMQAvD_BwE])
- <a id="eq-slide"></a>Thick cavity well slide (e.g., United Scientific, how thick and how large is the well?)
- <a id="eq-coverslip"></a>Coverslip (e.g, ???)
- <a id="eq-swab"></a>Cotton swab
- <a id="eq-polish"></a>Nail polish
- <a id="eq-glue"></a>Super glue (e.g., Loctite)

---

## Sample preparation

Sample preparation setup

1. **Make the agarose base medium (if we run out of it)**

- Weigh 1 g of agarose powder using the [scale](#eq-scale). Add the agarose powder to 100 mL of DI water in the [container](#eq-bottle), and place a [magnetic stir bar](#eq-stirbar) into the container.
- Place the container into a [beaker](#eq-beaker), then pour 200 mL of water into the beaker.
- Place the beaker on the [stirring hotplate](#eq-hotplate).
- Set the hotplate temperature to 150 °C and set the stirring speed to 7. Heat until the agarose is fully dissolved and the solution becomes clear (approximately 30 min).

1. **Heat up the agarose. (if we still have agarose in the container)**

- Slightly unscrew the cap of container of agarose.
- Turn on the [stirring hotplate](#eq-hotplate) and set the stirring speed to 7. Heat until the agarose is fully dissolved and the solution becomes clear (approximately 30 min).

1. **Make the tissue phantom samples.**

- Retrieve one [microcentrifuge tube](#eq-tubes) from the cabinet and place it into the [tube rack](#eq-rack). Using the pipettes from the pipette stand, pipette 4 µL of fluorescent beads with a [2–20 µL pipette](#eq-pipettes) and 40 µL of non-fluorescent polystyrene beads with a [20–200 µL pipette](#eq-pipettes) into the same tube. Dispose of the pipette tips into the sharps container.
- Using a 20–200 µL pipette, pipette 156 µL of agarose from the container and dispense it into the same microcentrifuge tube. Keep the pipette tip below the liquid surface to avoid bubbles, and mix by pipetting up and down quickly to ensure even mixing before the agarose starts to gel. Be sure to avoid generating bubbles during the process.
- Turn on the [mini vortexer](#eq-vortexer) and set the speed to 1400 rpm. Place the tube on the vortexer and mix thoroughly (approximately 40 second).
- Using a 20–200 µL pipette, pipette 135 µL of the mixture and dispense it into the [cavity slide](#eq-slide).
- Slowly lower the [coverslip](#eq-coverslip) from the side so that it gently covers the sample on the cavity slide and avoid pressing down forcefully to reduce bubble formation.
- Lightly press the coverslip with a [cotton swab](#eq-swab) to squeeze out and wipe any excess liquid from the edges using a cotton swab to keep the edges clean.
- Apply [nail polish](#eq-polish) to the four edges of the coverslip first to fix it in place and allow it to dry for approximately 5 mins.
- Once the nail polish is dry, apply [glue](#eq-glue) along the four edges of the coverslip to further enhance the seal.
- Mark the date and name of the sample on the slide.

1. **Shutdown and storage**

- Reduce the hotplate temperature and stirring speed to 0, then switch the [stirring hotplate](#eq-hotplate) off.
  > ⚠️ **Fire hazard:** Never leave the hotplate running unattended. If the water bath fully evaporates while the heater is still on, the residual agarose will carbonize and the container can ignite.
- Store the remaining agarose at room temperature and let it solidify into a gel as it cools.

---

## EAL measurement

1. **Background Measurement**

- Close the laser shutter so that there is no excitation light after the objective lens.
- In a dark environment, acquire multiple images under exactly the same imaging condition and image acquisition configurations as the rest of imaging sessions, except that the excitation laser is blocked.

1. **Pockels Cell Calibration (Optional)**

- This procedure is required if one does not know the absolute excitation laser power after the objective lens, and the laser power is controlled by a Pockels Cell.
- Open the laser shutter and set the laser to the desired wavelength.
- Gradually increase the Pockels cell control voltage and record the corresponding laser power after the beam passes through the objective lens.

1. **Determination of the Fluorescence Signal Strength in the Tissue Phantom**

- Place the tissue phantom slide on the sample stage. Bring the objective lens close to the slide surface (distance less than its working distance, e.g., 1 mm). Apply immersion medium between the objective and the slide.
- Set the laser power after the objective to a relatively low power (1-2 mW). Turn on the scanner and begin scanning the sample. Move the microscope z-stage with a step size of 10 µm to gradually move the objective away from the sample until fluorescence signal is first observed. Record the corresponding z-plane as $z_1$, which represents the lower boundary of the fluorescence volume.
- Continue raising the microscope until the fluorescence signal completely disappears. Record the corresponding z-plane as $z_2$, which represents the surface of the fluorescent sample.

1. **Scanning the Fluorescence Volume**

- Scan the same fluorescence volume ($z_2$ to $z_1$) using a series of different laser powers after the objective (maximum power: 5 mW).
- Use a step size of 10 µm between imaging planes.
- For each image, record its excitation laser power and its imaging depth.

---

## Data processing ([code](https://github.com/garyhost0630/Multiphoton-attenuation-length-measurement))

1. **Background Subtraction**

- Calculate the mean of the background images to obtain the background. Refer to [the procedure](#eal-measurement) describing how it was captured.
- If the backgrond is non-zero, subtract it from all the images.

1. **Determination of the Power Range for Unsaturated 2PE for each depth**

- For each imaging depth, calculate the mean intensity of the top 1% brightest pixels in the image as the fluorescence signal at each power.
- Perform a linear fit in log-log space using consecutive power values and their corresponding fluorescence signals, where the x-axis is $\log(\text{power})$ and the y-axis is $\log(\text{signal})$.
- Determine the appropriate power range such that the slope of the fitted line is closest to 2, indicating unsaturated 2PE, as shown in the figure below.


![Log-log fit of fluorescence signal vs power](images/power_slope_fit.png)


1. **Selection of the Depth Range for EAL Calculation**

- Using the method described in Step 2, determine the optimal power range and the corresponding linear fitting slope for each imaging depth. A summary of the results is shown in the figure below.
- Select a continuous depth range in which the optimal fitting slopes are close to or equal to 2. This depth range is then used for EAL calculation.


![Fitted slopes across imaging depths](images/depth_slope_summary.png)


1. **EAL estimation**

- For each selected depth, choose the second-highest power within the valid (non-saturated) power range and extract the corresponding fluorescence signal. Normalize the fluorescence signal by the excitation power.
- Perform a linear fit between imaging depth and the log of the normalized fluorescence signal.
- Obtain the slope $k$ and compute EAL using $\text{EAL} = -2/k$ as shown below.


![EAL linear fit](images/eal_fit.png)
