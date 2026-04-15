---
title: Academic Research Projects
layout: page
description: Summary of academic research projects in artificial intelligence and mechatronics.
bodyClass: page-thesis
---

# Academic Research Projects

## Bachelor of Science in Mechatronics (Graduated with Honors)
### Sistema de posicionamiento por odometría visual para AGVS
*(Positioning System for Autonomous Guided Vehicles using Visual Odometry)*

**Abstract**
This work aims to develop a positioning system for autonomous guided vehicles (AGVs) using visual odometry. The concept design was carried out using Ulrich and Dieter methodologies in order to select the system components and perform initial and integration tests on each of the elements. Odometry tests were carried out to select the best available feature detector-descriptor and to establish the rotational and linear velocities that the agent (RGB-D camera and AGV) should have when mapping its surroundings.

Based on this, five experiments were executed to determine the parameters with the best performance in both the mapping and the localization process. Within the results, the errors of the maps created by the experiments were calculated in order to determine which one had better performance. Finally, conditions and recommendations were generated to be able to scale the algorithms proposed in a real-time holonomic AGV.

**Keywords:** Visual odometry, SLAM, AGV, RGB-D camera

**Full paper (Spanish):** [Bachelor_VisualOdometry.pdf](https://github.com/victordpd19/victordpd19.github.io/blob/main/documents/Bachelor_VisualOdometry.pdf)

## Master of Science in Artificial Intelligence
### Desarrollo de un modelo de Deep Learning para el conteo y detección de animales en manadas densas a partir de imágenes aéreas
*(Development of a Deep Learning model for the counting and detection of animals in dense herds from aerial images)*

**Abstract**
This work presents an extension of the HerdNet architecture for multispecies wildlife detection and counting in aerial images, incorporating the Convolutional Block Attention Module (CBAM) and utilizing Hard Negative Patching (HNP) in a two-phase training scheme. Although the HerdNet+CBAM model did not surpass the results reported in previous state-of-the-art studies, it successfully improved performance compared to the baseline model implemented in this study, particularly in terms of per-class precision and validation stability. Furthermore, the application of HNP contributed to reducing false positives and improving discrimination between ambiguous background regions and true animal instances.

These findings position HerdNet+CBAM as a viable and promising alternative for automated wildlife analysis in complex environments, highlighting the importance of domain-adapting attention mechanisms and complementing architectures with robust training strategies. This study constitutes the first documented implementation of HerdNet combined with CBAM in this domain, offering a solid foundation for future research in ecological monitoring systems using computer vision.

**Keywords:** Object detection, animal counting, HerdNet, deep learning, aerial images, CBAM, DLA

**Full paper (Spanish):** [Master_HerdnetCBAM.pdf](https://github.com/victordpd19/victordpd19.github.io/blob/main/documents/Master_HerdnetCBAM.pdf)
