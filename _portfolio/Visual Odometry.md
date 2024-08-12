
---
title: "Visual Odometry using RGB-D Camera"
excerpt: "Developed a real-time camera motion estimation algorithm using RGB-D data, FAST feature detection, and Lucas-Kanade Optical Flow. <br/><br/><img src='/images/Visual_Odometry.jpg'>"
date: 2024-04-10
collection: portfolio
---

## About the Project

### Project Overview
Developed a real-time camera motion estimation algorithm using RGB-D data, FAST feature detection, and Lucas-Kanade Optical Flow. Created 3D point clouds from RGB images and predicted camera trajectory by fusing rotation and translation data. Implemented a Visual SLAM system with the Isaac ROS package and NVIDIA’s Isaac SDK for advanced localization and mapping, achieving precise pose estimation and autonomous robot navigation.

### Motivations
- **Understanding Movements**: Enabling robots to comprehend their surroundings by analyzing sequentially captured images.
- **Autonomous Navigation**: Helping robots understand their movements through onboard cameras, crucial for autonomous navigation.

### Challenges
- **Feature Detection**: Accurate feature detection and matching across frames.
- **Motion Estimation**: Estimating the rigid body transformation that best aligns features over time.
- **Global Drift**: Addressing unbounded global drift where errors accumulate over time without correction.

### Contributions
- **Algorithm Development**: Created a real-time camera motion estimation algorithm using RGB-D data.
- **3D Point Clouds**: Generated 3D point clouds from RGB images.
- **Camera Trajectory Prediction**: Predicted camera trajectory by fusing rotation and translation data.
- **Visual SLAM System**: Implemented a Visual SLAM system with the Isaac ROS package and NVIDIA’s Isaac SDK for advanced localization and mapping.

### Tools and Libraries
- **Python**: For algorithm development.
- **OpenCV**: For image processing and feature detection.
- **Isaac ROS Package**: For implementing Visual SLAM.
- **NVIDIA’s Isaac SDK**: For advanced localization and mapping.

### Visuals
- **Feature Detection**: Identifying features of interest in each frame.
- **Motion Estimation**: Estimating the motion of a camera in real-time using sequential images.
- **3D Point Clouds**: Visual representation of 3D point clouds generated from RGB images.
- **Camera Trajectory**: Predicted camera trajectory by fusing rotation and translation data.

<iframe width="560" height="315" src="https://www.youtube.com/embed/D1_2D2RZFw4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

This project showcases the practical utility of Visual Odometry in enabling robots to see and understand the world better.
