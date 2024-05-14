# Tropical Cyclone Damage Assessment

# YOLOv8s Model for Satelite Image Analysis

## Overview
This project utilizes the YOLOv8s model to analyze high-resolution satellite imagery for assessing damage caused by tropical cyclones. The model is specifically trained to identify damaged and undamaged residential and commercial buildings, providing crucial data for disaster response and recovery efforts.

## Data Preparation
### Tiling and Labeling
- The dataset was segmented into smaller tiles.
- Each tile was manually annotated using LabelMe to label the structures as damaged or undamaged.

### Model Training
- The labeled dataset was used to train the YOLOv8s model.
- Hyperparameters were fine-tuned through iterative training and testing phases to determine the optimal model configuration.
