#Brain Tumor Detection & Segmentation using Deep Learning

Overview

This project is a Deep Learning-based Brain Tumor Detection and Segmentation system developed using MRI images. The system uses a hybrid ResNet50 + U-Net architecture for accurate tumor segmentation and combines image preprocessing, texture feature extraction, and machine learning techniques for medical image analysis.

#The project focuses on:

MRI image preprocessing
Brain tumor segmentation
Texture feature extraction using GLCM
Deep learning model training
Tumor visualization and analysis
Features
Brain MRI tumor segmentation
ResNet50 encoder with U-Net decoder
Image preprocessing and augmentation
Texture feature extraction using GLCM
IoU-based evaluation metrics
Visualization of segmented tumor regions
Fine-tuning support for better accuracy
TensorFlow/Keras implementation
Tech Stack
Languages
Python
Libraries & Frameworks
TensorFlow / Keras
OpenCV
NumPy
Matplotlib
Scikit-image
Scikit-learn

#Project Workflow
MRI Image Dataset
        ↓
Image Preprocessing
        ↓
Tumor Segmentation
        ↓
Feature Extraction
        ↓
Deep Learning Model
        ↓
Tumor Analysis & Visualization
Model Architecture

#The project uses a custom hybrid architecture:

Encoder
ResNet50 pretrained on ImageNet
Extracts deep spatial features
Decoder
U-Net based upsampling layers
Skip connections for precise segmentation
Output
Segmented tumor mask
Tumor region visualization
Dataset

The dataset contains Brain MRI images along with corresponding tumor masks.

#Dataset used from Kaggle:

Brain MRI Segmentation Dataset
Image Processing Techniques
Preprocessing
Image resizing
RGB conversion
Normalization
ResNet preprocessing
Feature Extraction

#Gray Level Co-occurrence Matrix (GLCM) features:

Contrast
Correlation
Energy
Homogeneity
Evaluation Metrics

#The model is evaluated using:

IoU (Intersection over Union)
Accuracy
Loss curves
Visual segmentation comparison
