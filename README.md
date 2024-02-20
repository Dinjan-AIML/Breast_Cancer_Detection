# Breast Cancer Detection Project

## Overview
This project aims to develop a machine learning model for the early detection of breast cancer using various features extracted from breast tissue images. The model utilizes a dataset containing various attributes such as radius, texture, smoothness, compactness, etc., to predict whether a tumor is malignant or benign.


## Features
- **Radius**: Mean of distances from center to points on the perimeter.
- **Texture**: Standard deviation of gray-scale values.
- **Smoothness**: Variation in radius lengths.
- **Compactness**: Perimeter^2 / area - 1.0.
- **Concavity**: Severity of concave portions of the contour.
- **Concave Points**: Number of concave portions of the contour.
- **Symmetry**: Symmetry of tumor.
- **Fractal Dimension**: "Coastline approximation" - 1.

## Models
We experimented with several machine learning algorithms, including:
- Logistic Regression
- Decision Tree
- Random Forest

## Evaluation
The model's performance was evaluated using various metrics such as accuracy, precision, recall, and F1-score. Additionally, we used ROC curves and AUC scores to assess the model's ability to discriminate between malignant and benign tumors.

## Results
- Logistic Regression: 
  - Accuracy: 0.98

- Decision Tree: 
  - Accuracy: 1.00

- Random Forest: 
  - Accuracy: 0.96

## Usage
To use the model, you can follow these steps:
1. Clone this repository to your local machine.
2. Run the `Breast_Cancer_Detection.py` script to train and evaluate the models.
3. Use the trained model to make predictions on new data.
