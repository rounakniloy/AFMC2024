# Software Tool Name: ShipRes Version 1.0

*Please cite the following if you use this software tool.*

R. S. Niloy, M. S. Islam and A. Jahin, "Machine Learning-Based Resistance Prediction of AMECRC Hull," 24th Australasian Fluid Mechanics Conference (AFMC 2024) [under review].


## How to Install

1. Download the ShipRes.mlappinstall file:
   - You can download it from https://github.com/rounakniloy/AFMC2024/blob/main/ShipRes/ShipRes.mlappinstall.

2. Installation Requirements:
   - Ensure that MATLAB is installed on your system.

3. Installation Process:
   - After downloading, open the **ShipRes.mlappinstall** file. MATLAB will automatically handle the installation.


## How to Input Data

1. Setting Input Values:
   - After installation, open ShipRes and set the values for:
     - L/B (Length-to-Breadth ratio)
     - B/T (Breadth-to-Draft ratio)
     - CB (Block Coefficient)
     - Fn (Froude Number): This can be a single value or a range.
       - Minimum Fn value: 0.3
       - Maximum Fn value: 1.0

2. Prediction Process:
   - Once the values are set, click on the "Predict" button.
   - The predicted R_T/W (Total Resistance to Weight ratio) will be displayed on the right side of the ShipRes window.

3. Resetting Values:
   - You can reset the values of L/B, B/T, CB, and Fn by clicking the "Reset" button.


## How to Save Results

1. Saving Process:
   - Click on the "Save Result" button located below the figure.
   - This action will save the results as a text file in your current working directory (PWD).

2. File Naming Format:
   - The file name will be generated based on the input values:
     - Single Fn Value: LBx.xxx_BTx.xxx_CBx.xxx_Fnx.xxx.txt
     - Fn Range: LBx.xxx_BTx.xxx_CBx.xxx_Fnx.xx-xx.txt


## Output File Content

1. Displayed Information:
   - The output file will display the values of L/B, B/T, CB, and Fn.

2. R_T/W Prediction:
   - It will then show the R_T/W values corresponding to the given Fn.
   
   
## Contact Us
Should you require any assistance regarding **ShipRes Version 1.0**, feel free to contact the authors at-
- Rounak Saha Niloy (rniloy@student.unimelb.edu.au)
- Md. Shariful Islam (sharif.naoe@gmail.com)
- Abrar Jahin (azn1921@gmail.com)
