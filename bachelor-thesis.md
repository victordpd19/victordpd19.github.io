---
title: Bachelor of Science Thesis
layout: page
description: Detailed page for the Bachelor of Science thesis project.
bodyClass: page-thesis
---

# Bachelor of Science Thesis

## Sistema de posicionamiento por odometría visual para AGVS
*(Positioning System for Autonomous Guided Vehicles using Visual Odometry)*

### Overview

This thesis develops a visual odometry-based positioning system for Autonomous Guided Vehicles (AGVs). It follows Ulrich and Dieter methodologies for component selection, integration testing, and performance validation of the RGB-D sensor and mobile platform.

### Extended executive summary

The work presents the design, calibration, and validation of an inertial-visual navigation framework tailored for AGVs operating without reliable GPS. A Visual SLAM architecture was built using ROS, combining RGB-D sensing, feature-based odometry, and pose graph optimization to reduce drift and improve spatial accuracy in industrial navigation scenarios.

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

### Technical details

- Focus: visual odometry, SLAM, AGV navigation
- Tools: RGB-D sensing, ROS, feature detection, motion estimation
- Keywords: visual odometry, SLAM, AGV, RGB-D, ROS, industrial navigation

### Full paper

- [Bachelor_VisualOdometry.pdf](https://github.com/victordpd19/victordpd19.github.io/blob/main/documents/Bachelor_VisualOdometry.pdf)
