# Skin Cancer Detection Using Transfer Learning and MobileNetV2

## Project Overview
This project implements a deep transfer learning approach for melanoma skin cancer classification using the MobileNetV2 architecture. Leveraging the ISIC 2019 dermoscopic image dataset, the model achieves a high accuracy of 98.2% by addressing class imbalance through extensive data augmentation techniques.

## Key Features
- Utilizes MobileNetV2 pretrained on ImageNet for efficient melanoma vs. nevus classification.
- Employs data augmentation (rotation, shear, zoom, flip, brightness adjustments) to balance the dataset.
- Evaluates model performance with metrics: Accuracy, Precision, Recall, F1-Score, and AUC.
- Achieves state-of-the-art classification results suitable for real-time clinical applications.

## Dataset
- ISIC 2019 Challenge Dataset containing over 33,000 dermoscopic images.
- Balanced subset created with 8,170 melanoma and 8,170 nevus images for training.
- Dataset split: 70% training, 15% validation, 15% testing.

## Installation
1. Clone this repository:

