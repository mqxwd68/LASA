# LASA
Dataset of Lambertian-based Adversarial Attacks to Underwater Side-scan Sonar Image Classification Based on Convolutional Neural Networks

Url: https://drive.google.com/file/d/19cvCUYzCpMEjQb6o16s50Yf3YyEiSr_N/view?usp=share_link


.

    ├── root_images      # Originally gathered SSS image data  
    │   ├── train - classes 0/1/2  
    │   ├── test - classes 0/1/2 
    ├── rotate_images    # Data with rotations
    │   ├── train - classes 0/1/2
    │   ├── test - classes 0/1/2
    ├── color_cha_images $ Data with Photometric transformation (Color jitter)
    │   ├── train - classes 0/1/2
    │   ├── test - classes 0/1/2
	
	
|   | Class 0 (CP) | Class 1 (SHW) | Class 2 (PLW) |
| --- | --- | --- | --- |
| root samples | ![C_145](https://github.com/mqxwd68/LASA/blob/main/examples/C_145.jpg?raw=true) | ![S_001](https://github.com/mqxwd68/LASA/blob/main/examples/S_001.jpg?raw=true) | ![P_007](https://github.com/mqxwd68/LASA/blob/main/examples/P_007.jpg?raw=true) |
| rotate samples | ![C_082_rot119](https://github.com/mqxwd68/LASA/blob/main/examples/C_082_rot119.jpg?raw=true) | ![S_039_rot177](https://github.com/mqxwd68/LASA/blob/main/examples/S_039_rot177.jpg?raw=true) | ![P_023_rot253](https://github.com/mqxwd68/LASA/blob/main/examples/P_023_rot253.jpg?raw=true)  |
| colored samples |  ![C_002_col1417](https://github.com/mqxwd68/LASA/blob/main/examples/C_002_col1417.jpg?raw=true) | ![S_004_rot199_contr1242](https://github.com/mqxwd68/LASA/blob/main/examples/S_004_rot199_contr1242.jpg?raw=true) | ![P_002_rot072_col1431](https://github.com/mqxwd68/LASA/blob/main/examples/P_002_rot072_col1431.jpg?raw=true)   |
