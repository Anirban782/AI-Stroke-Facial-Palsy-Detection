# 🧠 AI-Based Facial Palsy Detection Using EfficientNetB0

A deep learning-based facial image classification system for detecting facial palsy using **EfficientNetB0 transfer learning**. The project combines image preprocessing, data augmentation, model training, performance evaluation, probability calibration, and **Grad-CAM explainability**.

## 📌 Overview

Facial palsy can cause noticeable asymmetry in facial features. This project explores the use of deep learning and computer vision to classify facial images based on facial-palsy-related patterns.

The system uses **EfficientNetB0**, pretrained on ImageNet, as the primary feature-extraction backbone and applies a binary classification layer for prediction.

A major component of the project is **Grad-CAM**, which provides visual explanations by highlighting image regions that influence the model's prediction.

## 🎯 Objectives

- Develop an automated facial-image classification pipeline.
- Apply transfer learning using EfficientNetB0.
- Improve training using image augmentation.
- Evaluate classification performance using multiple metrics.
- Analyze prediction confidence and calibration.
- Generate visual explanations using Grad-CAM.

## 🏗️ Architecture

```text
Facial Image
     ↓
Image Preprocessing
     ↓
Data Augmentation
     ↓
EfficientNetB0
     ↓
Global Average Pooling
     ↓
Dropout
     ↓
Dense Classification Layer
     ↓
Sigmoid
     ↓
Facial Palsy Prediction
     ↓
Grad-CAM Explanation