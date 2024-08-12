---
title: "MappingNYC: A Large-scale Multi-modality Dataset for Street Views in New York City"
subtitle:"AI4CE Lab, New York University"
excerpt: "Replica of Robotis OP3. <br/><br/><img src='/images/Shadow_Ghost.jpg'>"
date: 2024-04-10
collection: portfolio
---

## Hardware
1. Livox Mid360
2. Velodyne VLP 16
3. RTK GPS
4. Insta360 Air
5. Insta360 X2
6. Lattepanda 

## About the Project

### Project Overview
Designed and built a hardware mount housing sensors such as Livox Mid360, Velodyne VLP 16, RTK GPS, Insta360 Air, and Insta360 X2. Utilized 3D printing for the mount/prototypes and performed SMD soldering for reliable sensor integration and power distribution on the custom-designed board. Collected New York City image and LiDAR datasets, overlaying image data on LiDAR to generate a scalable 3D map.

### Motivations
- **Data Uniqueness**: NYC is unique for its urban complexity and traffic flows. No previous data exists that captures this complexity.
- **Multi-task Application**: The data enables multiple downstream tasks including autonomous driving, collaborative perception, visual place recognition, etc.

### Challenges in Mapping & Unique Aspects in MappingNYC
- **Environmental Variability**: Collecting consistent data across different weathers and seasons.
- **Technological Integration**: Efficiently integrating diverse equipment and software to maximize data utility and accuracy.
- **Hybrid Data Collection**: Combination of ground vehicle and robotic systems for a holistic urban mapping strategy.
- **Accessibility and Reach**: Extending data collection to previously inaccessible areas, enhancing urban analysis.

### Partial Results
- **LiDAR-SLAM**: Results from current LiDAR mapping methods show good but suboptimal results. We will optimize with our DeepMapping2.
- **V-SLAM**: Visual SLAM algorithms also suffer from accurate feature detection and loop closure detection.

### Contributions
- **Dual-Setup Approach**:
  - **Car-Mounted System**: Equipped with two LiDARs, two 360-cameras, IMU, and GPS for comprehensive data capture.
  - **Portable System**: An in-development portable apparatus for accessing off-road and indoor spaces.
- **Innovative Data Processing**:
  - **Enhanced Algorithms**: Improved algorithms for autonomous navigation through detailed urban datasets.
  - **Interactive Technology**: Demonstrations showing real-time data collection and processing.

### Visuals
- **Precision Mapping**: Detailed LiDAR-generated point cloud of an NYC street, showcasing data density and accuracy. Point cloud data visualization, color-coded to indicate varying elevations and structures.
- **Data Collection in Progress**: The equipped vehicle on a data-gathering mission, demonstrating the system’s operational setup. High-resolution capture of urban infrastructure, highlighting the nuanced data our technology provides. Synchronized dual camera feeds providing comprehensive visual data for enhanced mapping accuracy.
- **Real-World Application**: Our setup in action on the streets of NYC, capturing real-time data for urban mapping.

<iframe width="560" height="315" src="https://www.youtube.com/embed/D1_2D2RZFw4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
