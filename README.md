# 4D Perception

[](output/merged_mot_to_view.gif)

In this project, I learned how to do **3D object detection, tracking, and visualization** using LiDAR and camera data.  
The goal is to understand 3D perception pipelines and implement simplified but practical solutions inspired by SOTA methods.

PLease download [this folder](https://drive.google.com/file/d/1xgk9vJLT4d4Z1E17_risiuKUTW4NOx9j/view?usp=sharing) and put it inside the root project directory 

---

## 📌 Features
- Load and visualize sequences of images and LiDAR point clouds  
- 3D object detection and bounding box generation  
- 3D association across consecutive frames (tracking) using:
  - Geometric cost
  - Appearance cost
  - 3D IoU
- Complete 3D tracking pipeline implementation  
- Visualization of tracking results in 2D and 3D environments  

---

## 🚀 Project Workflow

1. **3D Object Detection & Visualization**  
   - Run 3D object detectors on sequences of LiDAR scans  
   - Visualize results in both 2D and 3D  

2. **3D Association & Tracking**  
   - Match objects across consecutive frames using multiple costs  

3. **3D Visualization & Full Tracking Pipeline**  
   - Load a LiDAR visualizer  
   - Implement a simplified tracker based on euclidean distance  
   - Project tracked objects onto video frames  
   - Visualize point clouds and 3D tracks in real-time  