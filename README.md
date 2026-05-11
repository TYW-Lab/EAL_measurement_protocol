# Effective attenuation length (EAL) measurement protocol

## Materials:

- [Agarose (Sigma Aldrich A4018-10G)](https://www.sigmaaldrich.com/US/en/product/sial/a4018)
- [1um fluorescent beads (Thermo Fisher F13081)](https://www.thermofisher.com/order/catalog/product/F13081?SID=srch-srp-F13081): $C_{fluo} = 1\times10^{7}\ \text{beads}/\text{µL}$
- [1um non-fluorescent polystyrene beads (Polysciences 07310)](https://polysciences.com/products/polybead-microspheres-100181m?srsltid=AfmBOorjVsqH1_RPydiDL_rl2QxODNqYwh8yssEixcAhqj7QJ9CAVFyL): $C_{poly} = 4.55\times10^{7}\ \text{beads}/\text{µL}$

---

## Dilution calculation

1. Take 1 g of agarose per 100 mL of water as the base medium.
2. The tissue phantom is prepared by mixing:

- Fluorescent beads: $V_{fluo} = 4\ \text{µL}$
- Non-fluorescent polystyrene beads: $V_{poly} = 40\ \text{µL}$
- Agarose solution: $V_{ag} = 156\ \text{µL}$

&nbsp;&nbsp;&nbsp;&nbsp; (a) The concentration of fluorescent beads:

$$
\frac{C_{fluo} \times V_{fluo}}{V_{fluo} + V_{poly} + V_{ag}}
= \frac{(1 \times 10^{7}\ \text{beads}/\text{µL}) \times (4\ \text{µL})}{(4 + 40 + 156)\ \text{µL}}
= 2 \times 10^{5}\ \text{beads}/\text{µL}
$$

&nbsp;&nbsp;&nbsp;&nbsp; (b) The concentration of non-fluorescent polystyrene beads:

$$
\frac{C_{poly} \times V_{poly}}{V_{fluo} + V_{poly} + V_{ag}}
= \frac{(4.55 \times 10^{7}\ \text{beads}/\text{µL}) \times (40\ \text{µL})}{(4 + 40 + 156)\ \text{µL}}
= 9.1 \times 10^{6}\ \text{beads}/\text{µL}
$$

&nbsp;&nbsp;&nbsp;&nbsp; (c) Ratio between non-fluorescent polystyrene beads and fluorescent beads:

$$
R = \frac{9.1 \times 10^{6}\ \text{beads}/\text{µL}}{2 \times 10^{5}\ \text{beads}/\text{µL}} = 45.5 : 1
$$

---

## Equipment and Supplies

![Sample preparation setup](images/sample_preparation.png)

1. <a id="eq-scale"></a>[Scale with 1mg precision (e.g., Amazon B0B18FVKX9)](https://www.amazon.com/LACHOI-Analytical-Electronic-Scientific-Interface（100g/dp/B0B18FVKX9/ref=sr_1_23?crid=53N44CR6E6CP&dib=eyJ2IjoiMSJ9.JxhvFY01RhwK801tdZU35q9rQTYcC2tQthYvrtRK_c9qMeJaWoobppvpIbADMv_egsUysH1QiAmutARfYbUVo3xsRe3cZ6kqu_ip90FScCJDGi5FgLu_) 
2. <a id="eq-bottle"></a>Heat resistant bottle for mixing and storing agarose solution
3. <a id="eq-hotplate"></a>[Cimarec stirring hotplate (e.g., Thermo Fisher SP88854100)](https://www.labdepotinc.com/cimarec-plus-stirring-hotplate-series?hsa_acc=5326096552&hsa_ad=&hsa_cam=21108713499&hsa_grp=&hsa_kw=&hsa_mt=&hsa_net=adwords&hsa_src=x&hsa_tgt=&hsa_ver=&utm_campaign=Zombie+SKU+PMax&utm_medium=ppc&utm_source=adwords&utm_term=) 
4. <a id="eq-tubes"></a>[Microcentrifuge tubes (e.g., Amazon B0BBV2LMW6)](https://www.amazon.com/Microcentrifuge-Sterilized-Plastic-Storage-Without/dp/B0BBV2LMW6/ref=sr_1_4?crid=25C67XB8W2600&dib=eyJ2IjoiMSJ9.xPCQBU3akLQF9rlTcVTk80aYDqlnaLlgpIB3o61syALNo4YVZ7pK2TRhUSHHzbtyePx1n4N1VfY8Aj9sUqRUC6LP2Sn7Orz1mKqxCnoEVPYP5y-dbozyev0I&th=1)
5. <a id="eq-rack"></a>[Tube rack (e.g., Amazon B0D8R66MQ1)](https://www.amazon.com/microcentrifuge-centrifuge-Holder-0-5ml-2ml-Centrifugal/dp/B0D8R66MQ1/ref=sr_1_3?crid=1ZI3PYB3G9CUW&dib=eyJ2IjoiMSJ9.YORppysqg2ETX3WIv1hENrcBaf5mFiQT1zwaMrziZxj4AO9c8Xdj1H7rB4cdGXhXPN5NPZLih2-Zv4NAnjZxWRS0aKGhmVgp_CD9SMFMh5y9FSw52Hk&th=1) 
6. <a id="eq-pipettes"></a>[Pipettes covering 2–20 µL and 20–200 µL volume ranges (e.g., Thermo Fisher F2-20R and Thermo Fisher F2-200R), stored in a pipette stand](https://pipette.com/F2-20R.html) 
7. <a id="eq-sharpcontainer"></a>Sharps disposal container (requested from the BU EHS department)
8. <a id="eq-vortexer"></a>[Vortexer (e.g., VWR IKA Model MV1)](https://www.marshallscientific.com/VWR-IKA-Model-MV1-Vortexer-p/vwr-ika.htm?srsltid=AfmBOop9bjFGTjvm6mfIoLMPdbEW2Kp7j4NSZWPVejsxydbgDRdUsfgK)

**Additional items not labeled in the figure:**

- <a id="eq-beaker"></a>[Beaker used as a water bath for heating and maintaining the agarose solution (e.g., Amazon B08X6KP8PS)](https://www.amazon.com/Feekoon-Measuring-Graduated-Cylinder-Cylinders/dp/B08X6KP8PS/ref=sr_1_4?dib=eyJ2IjoiMSJ9.fkiy-8L7Je-EhWoATqCnvyxkq-v-FXMNVzCA7z-qGeDNDcs54P547jp8ul-74plALojN6ZS2jLbsIO2a_mj1rIs66-stxX9k9EgyGbAiZ4CkSnhwNJoL-2j5WdnW8k42mjKDnWgq5s6cqeG)
- <a id="eq-stirbar"></a>[Magnetic stir bar (Amazon B08433BR2B)](https://www.amazon.com/Magnetic-Stirrer-Mixer-Laboratory-Magnet/dp/B08433BR2B/ref=sr_1_2_sspa?crid=196CI2UFZHRCA&dib=eyJ2IjoiMSJ9.BECz6XLmK0t2h23_xptReyUTl5H8ZWBFAkGMivEEslBczVqOcwe5r1wQVG_yIOzjQ9UYQqf0aYLCqZXuW098UgIffXQruAhnDwCammP35x5B738wfu_AB1LG1uUR9&th=1)
- <a id="eq-slide"></a>[Thick cavity well slide (e.g., United Scientific CSTK01 1-Concavity slide; 75 mm × 25 mm, 3 mm thick, concavity diameter ~16 mm, depth ~0.8 mm)](https://www.labdepotinc.com/p-12937-cavity-slides?utm_term=&utm_campaign=Zombie+SKU+PMax&utm_source=adwords&utm_medium=ppc&hsa_acc=5326096552&hsa_cam=22295522342&hsa_grp=&hsa_ad=&hsa_src=x&hsa_tgt=&hsa_kw=&hsa_mt=&hsa_net=adwords&hsa_ver=3&gad_source=1&ga)
- <a id="eq-coverslip"></a>[Coverslip (e.g., Thorlabs CG15CH2, #1.5H thickness, 22 mm × 22 mm)](https://www.thorlabs.com/item/CG15CH2)
- <a id="eq-swab"></a>[Cotton swab (e.g., VWR International 10806-000-PK)](https://www.labdepotinc.com/p-64-cotton-tipped-wooden-applicators?utm_term=&utm_campaign=Performance+Max+-+AGT&utm_source=adwords&utm_medium=ppc&hsa_acc=5326096552&hsa_cam=15278638752&hsa_grp=&hsa_ad=&hsa_src=x&hsa_tgt=&hsa_kw=&hsa_mt=&hsa_net=adwords&hsa)
- <a id="eq-polish"></a>[Nail polish (e.g., Amazon B0046MLZLG)](https://www.amazon.com/Sally-Hansen-Advanced-Nails-Fluid/dp/B0046MLZLG?th=1)
- <a id="eq-glue"></a>[Krazy Glue (e.g., Amazon B0BXMWDM42)](https://www.amazon.com/Krazy-Glue-EPIKG86648R-KG86648R-All-Purpose/dp/B0BXMWDM42/ref=sr_1_8?crid=2H3DLY2HBZ1CP&dib=eyJ2IjoiMSJ9.ZVQWAnzUL49sypVj2K7n-leSSrUo7HbydfUd-yI2bc795v5Pu9ScxNl3HniW7hCEcXaGtl3xIBKb4z0qt5psn8JYd0jh3G0daA0tnMldLPD4FYgdFbVpa6mZ_Phrbjb&th=1)

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

2. **Make the tissue phantom samples.**

- Retrieve one [microcentrifuge tube](#eq-tubes) from the cabinet and place it into the [tube rack](#eq-rack). Using the pipettes from the pipette stand, pipette 4 µL of fluorescent beads with a [2–20 µL pipette](#eq-pipettes) and 40 µL of non-fluorescent polystyrene beads with a [20–200 µL pipette](#eq-pipettes) into the same tube. Dispose of the pipette tips into the [sharps container](#eq-sharpcontainer).
- Using a 20–200 µL pipette, pipette 156 µL of agarose from the container and dispense it into the same microcentrifuge tube. Keep the pipette tip below the liquid surface to avoid bubbles, and mix by pipetting up and down quickly to ensure even mixing before the agarose starts to gel. Be sure to avoid generating bubbles during the process.
- Turn on the [mini vortexer](#eq-vortexer) and set the speed to 1400 rpm. Place the tube on the vortexer and mix thoroughly (approximately 40 second).
- Using a 20–200 µL pipette, pipette 135 µL of the mixture and dispense it into the [cavity slide](#eq-slide).
- Slowly lower the [coverslip](#eq-coverslip) from the side so that it gently covers the sample on the cavity slide and avoid pressing down forcefully to reduce bubble formation.
- Lightly press the coverslip with a [cotton swab](#eq-swab) to squeeze out and wipe any excess liquid from the edges using a cotton swab to keep the edges clean.
- Apply [nail polish](#eq-polish) to the four edges of the coverslip first to fix it in place and allow it to dry for approximately 5 mins.
- Once the [nail polish](#eq-polish) is dry, apply [glue](#eq-glue) along the four edges of the [coverslip](#eq-coverslip) to further enhance the seal.
- Mark the date and name of the sample on the slide.

3. **Shutdown and storage**

- Reduce the hotplate temperature and stirring speed to 0, then switch the [stirring hotplate](#eq-hotplate) off.
  > ⚠️ **Fire hazard:** Never leave the hotplate running unattended. If the water bath fully evaporates while the heater is still on, the residual agarose will carbonize and the container can ignite.
- Store the remaining agarose at room temperature and let it solidify into a gel as it cools.

---

## EAL measurement

1. **Background Measurement**

- Close the laser shutter so that there is no excitation light after the objective lens.
- In a dark environment, acquire multiple images under exactly the same imaging condition and image acquisition configurations as the rest of imaging sessions, except that the excitation laser is blocked.

2. **Pockels Cell Calibration**

- This procedure is required if one does not know the absolute excitation laser power after the objective lens, and the laser power is controlled by a Pockels Cell.
- Open the laser shutter and set the laser to the desired wavelength.
- Gradually increase the Pockels cell control voltage and record the corresponding laser power after the beam passes through the objective lens.

3. **Determination of the Fluorescence Signal Strength in the Tissue Phantom**

- Place the tissue phantom slide on the sample stage. Bring the objective lens close to the slide surface (distance less than its working distance, e.g., 1 mm). Apply immersion medium between the objective and the slide.
- Set the laser power after the objective to a relatively low power (1-2 mW). Turn on the scanner and begin scanning the sample. Move the microscope z-stage with a step size of 10 µm to gradually move the objective away from the sample until fluorescence signal is first observed. Record the corresponding z-plane as $z_1$, which represents the lower boundary of the fluorescence volume.
- Continue raising the microscope until the fluorescence signal completely disappears. Record the corresponding z-plane as $z_2$, which represents the surface of the fluorescent sample.

4. **Scanning the Fluorescence Volume**

- Divide the fluorescence volume ($z_2$ to $z_1$) into three sub-volumes along the axial direction.
- Start from the sub-volume closest to the sample surface and acquire image stacks using a relatively low excitation power range. Refer to [the procedure](#power-range-determination) describing how the power range maintaining the fluorescence signal within the non-saturated 2PE regime is determined.
- After completing the imaging of one sub-volume, increase the excitation power and move to the next deeper sub-volume.
- Repeat the same procedure for each subsequent sub-volume: determine an appropriate excitation power range and acquire the corresponding image stack.
- Use a step size of 10 µm between imaging planes.
- For each image, record its excitation laser power and imaging depth.

---

## Data processing ([Example](https://github.com/TYW-Lab/EAL_measurement_protocol/tree/main/example))

1. **Background Subtraction**

- Calculate the mean of the background image stack to obtain the averaged background image. Refer to [the procedure](#eal-measurement) describing how the background images were acquired.
- Subtract the averaged background image from all fluorescence images.
- Negative values after subtraction are clipped to zero.

<a id="power-range-determination"></a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2. **Determination of the Power Range for Unsaturated 2PE for Each Depth**

- For each imaging depth, extract fluorescence signals under different excitation powers.
- Convert EOM values to excitation power using `lookuptable.xlsx`.
- Calculate the fluorescence signal at each power as the mean intensity of the brightest `TOP_PERCENT` percent of pixels.
- Perform linear fits in log-log space using consecutive excitation powers and their corresponding fluorescence signals:
$$
\log(\text{Signal}) = k \log(\text{Power}) + b
$$
- Determine the appropriate excitation power range by selecting the contiguous fitting window whose slope is closest to `TARGET_TWO_PHOTON_SLOPE = 2.0`.
- An example of the fitting result is shown in the figure below.

![Log-log fit of fluorescence signal vs power](images/power_slope_fit.png)


3. **Selection of the Depth Range for EAL Calculation**

- Using the method described in Step 2, determine the optimal excitation power range and the corresponding fitted slope for each imaging depth.
- Plot the fitted slope as a function of imaging depth, as shown in the figure below.
- Select a continuous depth range in which the fitted slopes remain close to 2. The selected depth range is then used for EAL estimation.

![Fitted slopes across imaging depths](images/depth_slope_summary.png)

4. **EAL Estimation**

- For each selected imaging depth, choose the second-highest excitation power within the valid (non-saturated) power range and extract the corresponding fluorescence signal.
- Normalize the fluorescence signal by the excitation power:
$$
y = \log \left(\frac{S}{P^2}\right)
$$
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; where:
- $S$ is the fluorescence signal
- $P$ is the excitation power
- Perform a linear fit between imaging depth and the log-transformed normalized fluorescence signal.
- Obtain the fitted slope $k$ and compute the effective attenuation length (EAL) using:
$$
\text{EAL} = -\frac{2}{k}
$$
- An example of the EAL fitting result is shown in the figure below.


![EAL linear fit](images/eal_fit.png)
