---
title: Bachelor of Science Thesis (Extended Abstract)
layout: page
description: Detailed page for the Bachelor of Science project.
bodyClass: page-thesis
---


## Sistema de posicionamiento por odometría visual para AGVS
*(Positioning System for Autonomous Guided Vehicles using Visual Odometry)*

### Overview

This work develops a visual odometry-based positioning system for Autonomous Guided Vehicles (AGVs). It follows Ulrich and Dieter methodologies for component selection, integration testing, and performance validation of the RGB-D sensor and mobile platform.

### Extended executive summary

The work presents the design, calibration, and validation of an visual navigation framework tailored for AGVs operating without reliable GPS. A Visual SLAM architecture was built using ROS, combining RGB-D sensing, feature-based odometry, kinematic constraints and pose graph optimization to reduce drift and improve spatial accuracy in industrial navigation scenarios.

### Key contributions

- Designed a visual odometry system for AGV localization
- Integrated RGB-D sensing with a Turtlebot2 platform
- Evaluated ORB, BRISK, and GFTT feature detection strategies
- Implemented holonomic kinematic constraints and fiducial marker tracking for drift mitigation
- Validated the pipeline to achieve strong real-world localization accuracy

### Methodology

The system integrates an Intel RealSense D435i camera with an embedded NVIDIA Jetson Nano computer on a differential drive robot. Dynamic calibration corrected stereo and depth alignment, while the ROS-based pipeline used RTAB-Map for robust pose graph mapping.

### Results and impact

Through experiment-driven tuning, the best performing configuration combined Frame-to-Frame odometry, feature-based matching, holonomic constraints, and ArUco marker support. This approach reduced 3D reconstruction RMSE to approximately 0.038 meters and demonstrated viable scalability for industrial AGV applications.

### Media placeholders

1. **AGV hardware setup** — Placeholder for the vehicle and RGB-D camera configuration.
2. **Odometry workflow** — Placeholder for the visual odometry pipeline diagram.
3. **Mapping results** — Placeholder for sample map output or localization visualization.
4. **Performance metrics** — Placeholder for error charts or validation results.

### Visual assets

<figure style="text-align: center; margin: 20px auto;">
  <img src="/images/Thesis/Bachelor_Turtlebot_Foto.jpg" alt="AGV setup" style="max-height:260px; width:auto; display:block; margin:0 auto;" />
  <figcaption>AGV platform with RGB-D sensor and onboard computing module for visual odometry.</figcaption>
</figure>

<figure style="text-align: center; margin: 20px auto;">
  <img src="/images/Thesis/Bachelor_SIGTROVIndustrialPrototype_InternshipDevelopment.jpeg" alt="Industrial prototype development" style="max-height:260px; width:auto; display:block; margin:0 auto;" />
  <figcaption>Internship development prototype showing industrial AGV integration.</figcaption>
</figure>

<figure style="text-align: center; margin: 20px auto;">
  <img src="/images/Thesis/Bachelor_Camara_IR3.jpg" alt="Infrared camera frame" style="max-height:260px; width:auto; display:block; margin:0 auto;" />
  <figcaption>Infrared camera frame used for feature detection and depth sensing.</figcaption>
</figure>

<figure style="text-align: center; margin: 20px auto;">
  <img src="/images/Thesis/Bachelor_Camara_Nube1.png" alt="Camera and point cloud" style="max-height:260px; width:auto; display:block; margin:0 auto;" />
  <figcaption>Camera image overlaid with extracted point cloud for environment perception.</figcaption>
</figure>

<figure style="text-align: center; margin: 20px auto;">
  <img src="/images/Thesis/Bachelor_im_loc3.png" alt="Localization sample" style="max-height:260px; width:auto; display:block; margin:0 auto;" />
  <figcaption>Localization sample showing map alignment and pose estimation.</figcaption>
</figure>

<figure style="text-align: center; margin: 20px auto;">
  <img src="/images/Thesis/Bachelor_exp3_interfaz.png" alt="Localization interface" style="max-height:260px; width:auto; display:block; margin:0 auto;" />
  <figcaption>Localization and mapping interface showing live pose tracking and map state.</figcaption>
</figure>

<figure style="text-align: center; margin: 20px auto;">
  <img src="/images/Thesis/Bachelor_exp3_pointcloud.png" alt="Point cloud result" style="max-height:260px; width:auto; display:block; margin:0 auto;" />
  <figcaption>Point cloud reconstruction generated from RGB-D data during mapping.</figcaption>
</figure>

<figure style="text-align: center; margin: 20px auto;">
  <img src="/images/Thesis/Bachelor_exp3_opt2.png" alt="Optimized mapping output" style="max-height:260px; width:auto; display:block; margin:0 auto;" />
  <figcaption>Optimized map output after pose graph refinement and loop closure.</figcaption>
</figure>

<figure style="text-align: center; margin: 20px auto;">
  <img src="/images/Thesis/Bachelor_exp42_2d.png" alt="2D map result" style="max-height:260px; width:auto; display:block; margin:0 auto;" />
  <figcaption>2D mapping result used for navigation planning and validation.</figcaption>
</figure>

<figure style="text-align: center; margin: 20px auto;">
  <img src="/images/Thesis/Bachelor_exp42_sinLoop.png" alt="Mapping without loop closure" style="max-height:260px; width:auto; display:block; margin:0 auto;" />
  <figcaption>Mapping result without loop closure, showing raw pose drift and alignment errors.</figcaption>
</figure>

### Video assets

- **Post processing optimization** — [Google Drive link](https://drive.google.com/file/d/11icOaHPfBS3w5tmlcRYF_Frhx1nykp2o/view?usp=drive_link)
- **Mapping** — [Google Drive link](https://drive.google.com/file/d/1tiHhMz7deH2-xiuCvaglV8ac4qV_mAea/view?usp=drive_link)
- **Localization sample** — [Google Drive link](https://drive.google.com/file/d/15QPQYkhHOKruLKqn8opyaCsP_M9XS_KE/view?usp=drive_link)

> These video demos are linked externally to avoid heavy media rendering on GitHub Pages.

### Technical details

- Focus: visual odometry, SLAM, AGV navigation
- Tools: RGB-D sensing, ROS, feature detection, motion estimation
- Keywords: visual odometry, SLAM, AGV, RGB-D, ROS, industrial navigation

### Full paper

- [Bachelor_VisualOdometry.pdf](https://github.com/victordpd19/victordpd19.github.io/blob/main/documents/Bachelor_VisualOdometry.pdf)
