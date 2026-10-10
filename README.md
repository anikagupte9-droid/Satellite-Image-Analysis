# Satellite-Image-Analysis

# Detection of Water Bodies & Residential Zones Using Geo-Spatial Data Analysis and Machine Learning

A geospatial machine learning project that combines **Google Earth Engine, Sentinel-2 satellite imagery, and YOLOv8** to detect water bodies, agricultural land, and urban residential zones.

## Overview

This project aims to automate land-use detection from satellite imagery using deep learning. By combining satellite data acquisition, image preprocessing, and object detection, it explores applications in environmental monitoring, urban planning, and agricultural analysis.

## Objectives

- Automate the detection of water bodies and residential zones.
- Identify agricultural land using satellite imagery.
- Process Sentinel-2 data using Google Earth Engine.
- Train and evaluate a YOLOv8 object detection model.

## Tech Stack

- **Python** for data processing and model development
- **Google Earth Engine** for satellite imagery acquisition
- **Sentinel-2** for geospatial data
- **YOLOv8 & Ultralytics** for object detection
- **OpenCV** for image processing
- **Albumentations** for data augmentation

## Methodology

1. **Data Collection:** Extracted 256 × 256 RGB image patches from Sentinel-2 imagery for Mumbai's coastal region, rural Maharashtra, and Delhi.
2. **Preprocessing:** Organized the dataset, prepared annotations, applied augmentation, and used an 80:20 training-validation split.
3. **Model Training:** Trained a YOLOv8 model using transfer learning for 10 epochs with a batch size of 8.
4. **Evaluation:** Assessed detection performance using precision, recall, and mean Average Precision (mAP).

## Results

| Metric | Reported Value |
|---|---:|
| Precision | 0.92 |
| Recall | 0.89 |
| mAP@0.5 | 0.90 |
| Training Time | 25 minutes |

*Note: The report contains additional mAP figures that should be verified against the final evaluation output.*

## Applications

- Environmental and water-body monitoring
- Urban development and land-use mapping
- Agricultural land identification
- Climate monitoring and resource management

## Project Team

- Anika Gupte
- Nathan Varghese
- Dhiti Wadhwa


