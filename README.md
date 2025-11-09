
# Fingerprint -Based Blood Group Classification

A deep learning project that classifies blood groups from fingerprint images using multiple convolutional neural network architectures.


## Table of contents
 Introduction

· Features

· Dataset

· Installation

· Models

· Prediction

· Acknowledgements
## Introduction
This project implements a machine learning system that predicts blood groups (A, B, AB, O) from fingerprint images using various deep learning models including Simple CNN, ResNet50, InceptionV3, and VGG16. The system automatically selects the best performing model for predictions and provides confidence scores.
## Features
 Multiple Model Architectures: Implements four different CNN models

· Automatic Model Selection: Dynamically selects the best model based on performance metrics

· Confidence Scoring: Provides prediction confidence percentages

· User Feedback Loop: Optional validation system for continuous improvement

· Comprehensive Evaluation: Detailed performance metrics and confusion matrices
## Dataset
The project uses the Finger Print Based Blood Group Dataset from Kaggle, containing fingerprint images categorized by blood groups.
## Prerequisites
Python 3.7+

 Google Colab (recommended) or local environment with GPU support
## Models

The project implements and compares four neural network architectures:

1. Simple CNN

· Custom-built convolutional neural network
· Optimized for grayscale fingerprint images
· Lightweight and fast inference

2. ResNet50

· Pre-trained on ImageNet
· Transfer learning approach
· 50-layer residual network

3. InceptionV3

· Google's Inception architecture
· Efficient feature extraction
· Pre-trained weights

4. VGG16

· Oxford's VGG architecture
· 16-layer deep network
· Pre-trained on ImageNet
## Prediction

Input Requirements

· Fingerprint image (any standard format)
· Grayscale or color images accepted
· Automatic preprocessing handles format conversion

Output Format


blood group: [Predicted Blood Group]
best model decided for the pic u entered: [Selected Model Name]
surety percentage: [Confidence Score]%


## Acknowledgements
 
 Dataset provided by Rajan Marwin
· TensorFlow and Keras for deep learning frameworks
· Kaggle for dataset hosting platform
· Google Colab for computational resources

 
 
