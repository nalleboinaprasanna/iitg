# Delhi Airshed Land Use Classification
### SRIP 2026 — Earth Observation Assignment

## Overview
An end-to-end pipeline to classify land use patterns 
in the Delhi NCR region using satellite imagery and 
ESA WorldCover 2021 data.

## Pipeline
- Q1: Spatial gridding and image filtering
- Q2: Label construction and dataset preparation  
- Q3: CNN training and evaluation using ResNet18

## Dataset
- Sentinel-2 RGB patches (128×128, 10m resolution)
- ESA WorldCover 2021 (land_cover.tif)
- Delhi NCR and Airshed shapefiles

## Results
- Model: ResNet18 (pretrained, fine-tuned)
- Train/Test split: 60/40
- Evaluated using Accuracy, F1-score and Confusion Matrix

