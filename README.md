# Breast Cancer Histopathological Image Classification using AlexNet

This project implements transfer learning with AlexNet to classify breast cancer histopathological images as benign or malignant.

## Project Description

The code performs binary classification (benign vs malignant) on histopathological images from the BreaKHis dataset at 400X magnification using:
- Pretrained AlexNet model with transfer learning
- Layer freezing for the first 10 layers
- Data augmentation techniques
- Performance metrics including accuracy, sensitivity, specificity, and ROC curves

## Key Features

- Transfer learning implementation with AlexNet
- Image augmentation (flipping, translation, scaling)
- Model training with validation
- Performance evaluation including:
  - Accuracy calculations
  - ROC curve generation
  - Sensitivity and specificity metrics
- Model saving functionality

## Requirements

- MATLAB (tested on R2023b or later)
- Deep Learning Toolbox
- Image Processing Toolbox
- Pretrained AlexNet (can be downloaded when first run)

## Results

The model achieves:
- Validation accuracy: 94.686
- Test accuracy: 96.5217
- AUC scores: 99.5842
