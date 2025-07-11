---
title: "Projects"
permalink: /projects/
---

## Healthcare Applications
Generative models hold significant promise for addressing inverse problems in medical imaging by learning powerful data-driven priors that enhance image quality and recovery. These models can effectively capture complex anatomical structures and underlying data distributions, enabling improved performance in tasks such as super-resolution, inpainting, denoising, and image reconstruction. By incorporating prior knowledge directly into the solution process, generative approaches offer robust and efficient alternatives to traditional methods, particularly in scenarios with limited or noisy data, ultimately contributing to more accurate diagnostics and clinical decision-making.

<p align="center">
  <img src="{{ site.baseurl }}/images/stroke.jpeg" alt="Stroke Image" width="400"/>
  <br/>
  <em>Stroke lesion segmentation: Automated identification of stroke-affected regions in brain MRI scans using deep learning.</em>
</p>
<p align="center">
  <img src="{{ site.baseurl }}/images/tumor_inpainting.png" alt="Tumor Inpainting" width="400"/>
  <br/>
  <em>Tumor inpainting: Generative models reconstruct missing or corrupted tumor regions in medical images for improved diagnosis.</em>
</p>
<p align="center">
  <img src="{{ site.baseurl }}/images/tumor_progression.png" alt="Tumor Progression" width="400"/>
  <br/>
  <em>Tumor progression prediction: AI-driven analysis forecasts the growth and development of tumors over time from imaging data.</em>
</p>

## Geoscience Applications
We developed an automated pipeline for geologic map feature extraction that leverages AI to identify and interpret map elements. The system first extracts map units from the legend, then uses a prompt-based approach to perform open-set extraction of polygon and point features, using the legend items as prompts to guide the process.

<p align="center">
  <img src="{{ site.baseurl }}/images/map_polygon_segmentation.png" alt="Map Polygon Segmentation" width="400"/>
  <br/>
  <em>Model performance on polygon feature extraction after aggregating all polygon and point features across the entire map.</em>
</p>

## The Confluence of AI for Scientific Simulation
Physics-constrained learning methods incorporate known physical laws—such as conservation laws or differential equations—directly into the training of machine learning models. By embedding these constraints into the model architecture or loss function, they ensure that predictions remain consistent with established scientific principles. This approach enhances model accuracy, generalization, and interpretability, especially in data-scarce scenarios. Applicable across a wide range of scientific simulations—including fluid dynamics, structural mechanics, and climate modeling—physics-constrained methods bridge the gap between data-driven models and traditional physics-based approaches.