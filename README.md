# Image Segmentation usinf Deep Learning with Pytorch

# Overview

This project implements image segmentation using deep learning techniques with PyTorch. The segmentation model is trained on an augmented dataset and optimized using evaluation metrics such as the Dice Coefficient to improve accuracy. The primary architecture used for segmentation is U-Net, a widely adopted model for pixel-wise image classification.

# Features

- # Preprocessing & Data Augmentation:
   Applies transformations such as rotation, flipping, and normalization to improve model generalization.
- # Deep Learning-based Segmentation:
  Implements a U-Net architecture trained using PyTorch for high-quality segmentation.
- # Evaluation Metrics:
  Assesses segmentation performance using Dice Coefficient, IoU (Intersection over Union), and Pixel Accuracy.
- # Scalable Training Pipeline:
   Supports GPU acceleration for efficient model training.

# Dataset 

The dataset consists of labeled images for segmentation tasks. Data preprocessing includes:
-Resizing images to a standard dimension.
-Applying transformations such as normalization, flipping, and rotation.
-Splitting into training, validation, and test sets.

https://github.com/VikramShenoy97/Human-Segmentation-Dataset

# Results

The model's performance is evaluated using:

- # Dice Coefficient:
  Measures the overlap between predicted and ground truth masks.
- # IoU (Jaccard Index):
  Quantifies the intersection over union of the predicted mask.
- # Pixel Accuracy:
   Computes the ratio of correctly classified pixels.
