# Breast Cancer Detection — Multi-Task Deep Learning Explainability
This repository provides explainability analysis for a multi-task deep learning model (InceptionResNetV2 + ASPP) trained for breast ultrasound image classification (normal, benign, malignant) and lesion segmentation. The project includes Grad-CAM, Guided Grad-CAM, and Integrated Gradients visualizations.

## Features
- Multi-task model: classification + segmentation  
- Explainability methods:
  - Grad-CAM  
  - Guided Grad-CAM  
  - Integrated Gradients  
- Batch processing for the full test set  
- Saves heatmaps, overlays, and comparison images
