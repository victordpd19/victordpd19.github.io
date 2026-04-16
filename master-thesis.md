---
title: Master Of Science Thesis (Extended Abstract)
layout: page
description: Detailed page for the Master of Science thesis project.
bodyClass: page-thesis
---

# Master Of Science Thesis (Extended Abstract)

## Desarrollo de un modelo de Deep Learning para el conteo y detección de animales en manadas densas a partir de imágenes aéreas
*(Development of a Deep Learning model for the counting and detection of animals in dense herds from aerial images)*

### Overview

This work extends the HerdNet architecture for multispecies wildlife detection and counting in aerial imagery. It integrates the Convolutional Block Attention Module (CBAM) and Hard Negative Patching (HNP) into a two-phase training pipeline to improve precision and validation stability in highly complex natural scenes.

This project is based on the original HerdNet research and implementation. The HerdNet repository is available at [https://github.com/Alexandre-Delplanque/HerdNet](https://github.com/Alexandre-Delplanque/HerdNet).

### Extended executive summary

This work details the conception, implementation, and empirical evaluation of an advanced convolutional architecture based on the HerdNet paradigm, designed for point-based detection and multispecies enumeration within aerial orthophotography (UAVs). The work addresses severe occlusion, appearance ambiguity, uneven illumination, and extreme density in wildlife scenes by combining attention-based feature recalibration with adaptive hard negative sampling.

### Key methodological contributions

- **Attention augmentation with CBAM:** Integrated sequential channel and spatial attention modules to recalibrate intermediate feature maps and improve discrimination of animals from background clutter.
- **Backbone model analysis:** Compared DLA-34 and DLA-60 backbones to identify overfitting thresholds and demonstrate that larger models do not always yield better generalization without proper regularization.
- **Hard Negative Patching:** Applied HNP to emphasize visually deceptive background patches, reducing false positives among ambiguous species and sharpening model decision boundaries.
- **Domain-specific validation:** Calibrated architecture complexity to the aerial animal detection domain, emphasizing parsimonious design over excessive parameter growth.

### Results and impact

The HerdNet+CBAM model delivered measurable improvement over the study baseline, particularly in difficult background regions and multi-species scenes. It achieved an F1-score of 0.704 on the evaluation set and established a strong foundation for future work in autonomous perception for wildlife monitoring.

### Media placeholders

1. **Architecture diagram** — Placeholder for the HerdNet+CBAM model architecture illustration.
2. **Training pipeline** — Placeholder for the two-phase training and hard negative patching workflow.
3. **Detection examples** — Placeholder for sample aerial image outputs and predicted bounding regions.
4. **Evaluation chart / video** — Placeholder for precision/recall visualizations or a short demo.

### Visual assets

<figure>
  <img src="/images/Thesis/MASTER_Arquitectura_Herdnet.png" alt="HerdNet architecture" style="max-height:260px; width:auto; display:block; margin:0 auto;" />
  <figcaption>HerdNet architecture diagram used for feature extraction and detection.</figcaption>
</figure>

<figure>
  <img src="/images/Thesis/MASTER_cbam_arquitectura.png" alt="CBAM module diagram" style="max-height:260px; width:auto; display:block; margin:0 auto;" />
  <figcaption>CBAM attention module integration for channel and spatial attention.</figcaption>
</figure>

<figure>
  <img src="/images/Thesis/MASTER_imagen ampliada.jpg" alt="Aerial detection example" style="max-height:260px; width:auto; display:block; margin:0 auto;" />
  <figcaption>An example aerial image used to validate dense herd detection performance.</figcaption>
</figure>

<figure>
  <img src="/images/Thesis/MASTER_MaiaStreamlit.png" alt="Maia Streamlit UI" style="max-height:260px; width:auto; display:block; margin:0 auto;" />
  <figcaption>UI screenshot of the Maia Streamlit application used for model deployment and interaction.</figcaption>
</figure>

### Technical details

- Model: HerdNet + CBAM
- Domain: aerial wildlife detection and counting
- Techniques: attention mechanisms, hard negative mining, two-phase training
- Keywords: object detection, animal counting, HerdNet, deep learning, aerial images, CBAM, DLA

### Project repository

- [Backend, frontend, and Streamlit deployment (Spanish)](https://github.com/victordpd19/maia_proyecto_final)

### Full paper

- [Master_HerdnetCBAM.pdf](https://github.com/victordpd19/victordpd19.github.io/blob/main/documents/Master_HerdnetCBAM.pdf) — paper in Spanish
