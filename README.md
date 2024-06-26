# LASA
Dataset of the paper [**Lambertian-based adversarial attacks on deep-learning-based underwater side-scan sonar image classification**](https://www.sciencedirect.com/science/article/pii/S003132032300064X?via%3Dihub)

### URL
https://drive.google.com/file/d/1Gy3kap2nRfQ4ndbjX_tExGF_IrMBR8vh/view?usp=sharing

Three categories in total: Corpse (label 0) / Shipwreck (label 1) / Plane Wreckage (label 2) 
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
	
	
### Visualization of Samples	
|   | Class 0 (CP) | Class 1 (SHW) | Class 2 (PLW) |
| --- | --- | --- | --- |
| root samples | ![C_145](https://github.com/mqxwd68/LASA/blob/main/examples/C_145.jpg?raw=true) | ![S_001](https://github.com/mqxwd68/LASA/blob/main/examples/S_001.jpg?raw=true) | ![P_007](https://github.com/mqxwd68/LASA/blob/main/examples/P_007.jpg?raw=true) |
| rotate samples | ![C_082_rot119](https://github.com/mqxwd68/LASA/blob/main/examples/C_082_rot119.jpg?raw=true) | ![S_039_rot177](https://github.com/mqxwd68/LASA/blob/main/examples/S_039_rot177.jpg?raw=true) | ![P_023_rot253](https://github.com/mqxwd68/LASA/blob/main/examples/P_023_rot253.jpg?raw=true)  |
| colored samples |  ![C_002_col1417](https://github.com/mqxwd68/LASA/blob/main/examples/C_002_col1417.jpg?raw=true) | ![S_004_rot199_contr1242](https://github.com/mqxwd68/LASA/blob/main/examples/S_004_rot199_contr1242.jpg?raw=true) | ![P_002_rot072_col1431](https://github.com/mqxwd68/LASA/blob/main/examples/P_002_rot072_col1431.jpg?raw=true)   |

Research only. 
Commercial use is strictly prohibited.

### Reference
If you use this dataset please cite it as follows
```
@article{ma2023lambertian,
  title={Lambertian-based adversarial attacks on deep-learning-based underwater side-scan sonar image classification},
  author={Ma, Qixiang and Jiang, Longyu and Yu, Wenxue},
  journal={Pattern Recognition},
  volume={138},
  pages={109363},
  year={2023},
  publisher={Elsevier}
}
```
