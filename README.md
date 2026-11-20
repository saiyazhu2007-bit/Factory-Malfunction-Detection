# Geospatial AI-Based Pneumonia Detection

## Project Overview

This project presents an AI-powered approach to pneumonia detection by integrating Deep Learning, Explainable AI (XAI), and Geospatial Information Systems (GIS). It aims to support pneumonia identification through medical image analysis and visualize geographical disease-related insights.

The system uses a **MobileNetV2-CBAM deep learning architecture** for image classification, Grad-CAM for visual explanation, and GIS techniques for geographical visualization and spatial analysis.

## Objectives

- Develop an AI-based model for pneumonia detection from chest X-ray images.
- Improve feature extraction using MobileNetV2 integrated with CBAM attention.
- Apply Explainable AI techniques to highlight important image regions.
- Integrate geospatial visualization for geographical health analysis.
- Explore the potential of combining AI and GIS for healthcare applications.

## Technologies Used

| Category | Technologies |
|---|---|
| Programming | Python |
| Deep Learning | TensorFlow / Keras |
| CNN Architecture | MobileNetV2 |
| Attention Mechanism | CBAM |
| Explainable AI | Grad-CAM |
| Geospatial Analysis | GIS |
| Visualization | Interactive Dashboard |
| Development | Jupyter Notebook |

## Methodology

### 1. Data Preparation
Medical chest X-ray images are prepared and processed for deep learning-based classification.

### 2. Feature Extraction and Classification
MobileNetV2 is used as the feature extraction backbone, while the Convolutional Block Attention Module (CBAM) enhances the model's ability to focus on relevant image features.

### 3. Pneumonia Detection
The trained deep learning model performs image classification to identify pneumonia-related patterns.

### 4. Explainable AI
Grad-CAM generates visual heatmaps that help interpret the regions of chest X-ray images influencing model predictions.

### 5. Geospatial Visualization
GIS techniques are incorporated to explore geographical patterns and present disease-related information through visualization.

## Model Performance

The developed model achieved the following reported evaluation results:

- **Accuracy:** 89%
- **AUC Score:** 0.96

These results represent the model's reported performance during evaluation.

## Key Features

- Deep learning-based pneumonia classification.
- MobileNetV2 with CBAM attention mechanism.
- Grad-CAM-based visual explanations.
- Integration of AI and geospatial analysis.
- Geographical disease visualization.
- Research-oriented healthcare analytics.

## Repository Structure

```text
Geospatial-Al-Pneumonia-Detection/
│
├── Geospatial_Al_Pneumonia_Reconstructed.ipynb
│
├── Pneumonia_GeoAl_Paper.docx
│
├── Geospatial_Al_Pneumonia_Detection_Poster_MIGARS2026_3(1).pptx
│
├── pneumonia_project.zip
│
└── README.md
```

## Research and Publication

This project was presented as a poster at **IEEE MIGARS 2026**, held from 20–22 July 2026.

**Paper ID:** MIGARS2026-206

The research explores the integration of deep learning, explainable AI, and geospatial intelligence for pneumonia detection and geographical health analysis.

## Applications

- AI-assisted medical image analysis.
- Healthcare data visualization.
- Geospatial disease monitoring.
- Explainable deep learning research.
- Smart healthcare analytics.

## Future Enhancements

- Develop automated geographical disease data updates.
- Integrate real-time healthcare datasets.
- Improve model generalization using larger and diverse datasets.
- Enhance interactive GIS dashboard capabilities.
- Explore deployment as a web-based healthcare analytics platform.

## Disclaimer

This project is developed for academic and research purposes. The model is not intended to replace professional medical diagnosis or clinical decision-making.

## Acknowledgement

Developed as a research project exploring the combination of Artificial Intelligence, Deep Learning, Explainable AI, and Geospatial Technologies for healthcare applications.

---

**Keywords:** Geospatial AI | Pneumonia Detection | Deep Learning | MobileNetV2 | CBAM | Grad-CAM | GIS | Explainable AI | Healthcare Analytics
