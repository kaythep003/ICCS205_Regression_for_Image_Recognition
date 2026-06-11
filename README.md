# Chihuahua vs. Muffin Image Classification

## Overview

A simple image classification project that distinguishes between Chihuahua and muffin images using numerical methods and linear regression. Instead of using deep learning frameworks, the classifier was built from scratch using image preprocessing, feature extraction, and a closed-form linear regression model.

## Technologies

* Python
* NumPy
* Matplotlib
* PIL (Python Imaging Library)
* Jupyter Notebook

## Key Tasks

* Collected and prepared image datasets from Kaggle
* Implemented image preprocessing (grayscale conversion, resizing, normalization)
* Extracted numerical features from images, including:

  * Mean intensity
  * Contrast (standard deviation)
  * Symmetry measurements
  * Texture and gradient-based features
* Developed a linear regression classifier using the Normal Equation
* Evaluated model performance using confusion matrices and accuracy metrics

## Results

* Achieved approximately 77% training accuracy
* Achieved approximately 75% accuracy on CAPTCHA-style test images
* Identified texture gradients as the most influential feature for classification

## Skills Demonstrated

* Numerical Methods
* Feature Engineering
* Image Processing
* Machine Learning Fundamentals
* Linear Algebra Applications
* Model Evaluation and Analysis
