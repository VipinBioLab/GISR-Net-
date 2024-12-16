# GoogLeNet-based Image-to-Scalar Regressor for Quality Assessment of Illumination Correction in Dermatological Macro-Images

This repository features a task-specific deep learning model named **GoogLeNet-based Image-to-Scalar Regressor Network (GISR-Net)** for assessing the quality of illumination-corrected macroscopic images. The implementation includes MATLAB codes.

---

## Running the GISR-Net Demo

1. **Download the Test Data**  
   Download the `Nonuniform_Illumination_Macro-images.zip` file containing 50 test images and extract its contents.

2. **Download the Test Metadata**  
   Obtain the `Test.csv` file, which provides details about the test images and their corresponding DSI scores.

3. **Download the MATLAB Files**  
   Download all the required MATLAB files from the repository.

4. **Organize the Files**  
   Place the following in a single directory (e.g., `Demo`):  
   - All MATLAB files  
   - The `Test.csv` file  
   - The extracted `Nonuniform_Illumination_Macro-images` folder

5. **Run the GISR-Net Testing Script**  
   Execute the `Testing_GISRNet.m` or `Testing_GISRNet_Model.mlx` file to compute the GICQI scores for the test images.

---

## Note

The full training dataset and MATLAB codes will be made available after the associated paper is accepted.

