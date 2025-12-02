# Agriculture-Vision
A lightweight, real-time crop-health monitoring system using YOLO-based plant disease detection and RGB-driven NDVI estimation, optimized for deployment on the NVIDIA Jetson Nano. Trained on PlantVillage and validated with SEN12MS vegetation-index ground truth.


------------------ Setup Instructions -----------------------

A. Set Up on Laptop/PC (for training): Install required Python libraries
B. Set Up Jetson Nano (for deployment):
   1. Install JetPack 4.x
   2. Make sure CUDA, cuDNN, and OpenCV are installed
   3. Install PyTorch (Jetson-compatible version)
   4. Install YOLO
   5. Convert YOLO model to TensorRT


------------------ Dependencies -------------------------

These Python packages are required:

1. ultralytics
2. opencv-python
3. numpy
4. torch
5. torchvision
6. matplotlib
7. tqdm
8. scikit-learn


Jetson Nano also needs:

1. JetPack 4.x
2. CUDA
3. cuDNN
4. PyTorch (Jetson version)
5. OpenCV
6. TensorRT

----------------- Usage Notes --------------------------

A. Train YOLO Model: Run YOLO training on PlantVillage
B. Run NDVI Estimation
C. Run Real-Time Detection on Jetson Nano
D. Dataset Information

Full datasets must be downloaded separately.
Links are provided in:
/data/datasets.md

