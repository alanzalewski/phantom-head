# Phantom Head

This phantom head was created for use in NIOSH-compliant respiratory mask testing. The [CAD files](https://github.com/alanzalewski/phantom-head/tree/main/V4%20(final)/CAD%20Files) can be found in the V4 file in this repository.

## Development
We used publically available [ISO digital headforms](https://www.cdc.gov/niosh/npptl/topics/respirators/headforms/default.html) (specifically the medium size)—which were developed from anthropomteric data collected by NIOSH—as our base. The head itself was printed at 90% scale, with the remaining 10% filled with silicone to simulate a layer of human flesh and to provide a seal for each mask tested. The head went through four design iterations, as detailed below, before reaching the final design used in testing. Meshmixer was used to create all the CAD files, and the head was cast with Smooth-On's Ecoflex 00-30 silicone.

### V1
<p align="left"> 
  <img src="https://github.com/alanzalewski/phantom-head/blob/main/V1/V1_1.png" width="200" alt="3/4 view of V1 phantom head"> 
  <img src="https://github.com/alanzalewski/phantom-head/blob/main/V1/V1_2.png" width="155" alt="side view of V1 phantom head"> 
  <img src="https://github.com/alanzalewski/phantom-head/blob/main/V1/V1_3.png" width="203" alt="back view of V1 phantom head"> 
</p>

The initial version of the head included a tube that ran from the mouth out through the back of the head, exiting into a hollowed out portion that would provide users with the necessary room to adjust respiratory tubing. The front part of the tube was only 2mm thick, and extended out quite far (in line with the tip of the nose), which was likely to be too flimsy once actually printed.

### V2
<p align="left"> 
  <img src="https://github.com/alanzalewski/phantom-head/blob/main/V2/V2_1.png" width="200" alt="3/4 view of V2 phantom head"> 
  <img src="https://github.com/alanzalewski/phantom-head/blob/main/V2/V2_2.png" width="178" alt="side view of V2 phantom head"> 
  <img src="https://github.com/alanzalewski/phantom-head/blob/main/V2/V2_3.png" width="194" alt="back view of V2 phantom head"> 
</p>

The following changes were made to V1:
* The thickness of the front tube was increased from 2mm to 3.5mm to ensure it would print without snapping during the removal of supports or insertion of tubing.
* The front tube was also shortened slightly to better fit into masks. Where V1 had the tube aligned with the tip of the nose, V2 goes approximately halfway.
* The hole in the back was made diamond-shaped to reduce the need for supports in that area when printing.
* The compexity of the back tube was reduced.

This version of the head was printed at 40% scale, along with a negative mold at 50% scale to test the silicone mold-making process, as shown below. (Note: this initial version of the mold mold was not printed with a hole to pour silicone through; that was drilled into the mold once it was printed.)

<p align="left"> 
  <img src="https://github.com/alanzalewski/phantom-head/blob/main/V2/V2_test.png" width="300" alt="side view of the silicone covered V2 head sitting in half its mold"> 
</p>

### V3
<p align="left"> 
  <img src="https://github.com/alanzalewski/phantom-head/blob/main/V3/V3_1.png" width="200" alt="3/4 view of the printed V3 phantom head"> 
  <img src="https://github.com/alanzalewski/phantom-head/blob/main/V3/V3_mold1.png" width="215" alt="the updated mold, with the V2 test head sitting inside"> 
</p>

The following changes were made to V2:
* The head was scaled to 90%, while the tubing inside the head was designed at 100% scale, so the entire head file could be printed as-is, while allowing the head to fit its mold with a 10% gap for silicone and to maintain proper tube sizing.
* Both the front and back tubes were given an inner diameter of 25mm, with a 2mm thickness (i.e. one continuous tube).
* The front tube was brought forward by roughly 1cm to make it easier to cut away any excess silicone after molding, allowing tubing to be attached to the front of the head. (Note that in our V2 silicone mold test, the silicone has completely covered the front tube in the mouth area.)
* A diamond shaped plud was also printed to place in the hole in the back to help prevent silicone from seeping in during the pouring process.
* A hole for pouring the silicone in through was made in the mold prior to printing. As the mold was quite a large one, it was printed in 8 separate pieces to accomodate the 3D printers' size limitations. Similarly, the head was printed in 2 separate pieces.

### V4
<p align="left"> 
  <img src="https://github.com/alanzalewski/phantom-head/blob/main/V4%20(final)/Images/V4_1.png" width="269" alt="close-up of the back of the V4 head, with tubing"> 
  <img src="https://github.com/alanzalewski/phantom-head/blob/main/V4%20(final)/Images/V4_2.png" width="263" alt="side view of the V4 head"> 
  <img src="https://github.com/alanzalewski/phantom-head/blob/main/V4%20(final)/Images/V4_3.jpg" width="344" alt="front view of the V4 head, in front of the mold"> 
</p>

The following changes were made to V3:
* The continuous tube's thickness was increased to 3mm (while still maintaining a 25mm internal diameter) and a volume of 40mL based on NIOSH CO2 testing requirements. 
* The mold was left unchanged from V3, but the head was separated into and printed in 3 separate pieces, both due to printer size limitations and to maintain the structural integrity of the tube (i.e. by allowing the tube to print vertically, eliminating the need for supports there).
* The head ended up being too front-heavy to stand on its own, so a stand was printed in 2 pieces to provide stability.

Final images of the phantom head, fully complete:
<p align="left"> 
  <img src="https://github.com/alanzalewski/phantom-head/blob/main/V4%20(final)/Images/V4_4.jpg" width="225" alt="side view of the complete V4 head"> 
  <img src="https://github.com/alanzalewski/phantom-head/blob/main/V4%20(final)/Images/V4_5.jpg" width="400" alt="complete head, with stand and mask, during testing"> 
</p>
