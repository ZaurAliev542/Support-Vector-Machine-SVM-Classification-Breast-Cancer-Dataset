# Support-Vector-Machine-SVM-Classification-Breast-Cancer-Dataset
A practical implementation of Support Vector Machine classification using the Breast Cancer Wisconsin dataset from scikit-learn, including feature scaling, RBF kernel, model training, prediction, and performance evaluation.
# Support Vector Machine (SVM) Classification

## Overview

This project demonstrates the implementation of a Support Vector Machine (SVM)
classifier using the Breast Cancer Wisconsin dataset provided by scikit-learn.

The objective is to classify breast tumors as malignant or benign based on
30 numerical features describing tumor characteristics.

## Methodology

The machine learning pipeline consists of:

1. Dataset loading
2. Feature and target separation
3. Train-test splitting
4. Feature standardization
5. SVM model construction
6. Model training
7. Prediction
8. Model evaluation

## Model

The classifier uses an SVM with an RBF (Radial Basis Function) kernel.

Key hyperparameters:

- Kernel: RBF
- C: 1.0
- Gamma: "scale"

## Evaluation

Model performance is evaluated using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-score

## Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
