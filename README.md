# Feature Selection using RFECV with SVM

## Overview
This project demonstrates automatic feature selection 
using Recursive Feature Elimination with Cross Validation (RFECV) 
combined with a Support Vector Machine (SVM) classifier.

## Dataset
Breast Cancer dataset from scikit-learn.

The dataset contains numerical features extracted from digitized images 
of breast mass tissue samples. The task is binary classification 
(malignant vs benign).

## Methodology

1. Data split into training and testing sets.
2. Feature scaling applied using StandardScaler.
3. Linear SVM used as the base classifier.
4. RFECV automatically determines the optimal number of features 
   using 5-fold cross-validation.
5. Final model trained using selected features.
6. Model evaluated using accuracy and classification report.

## Key Concepts Demonstrated

- Feature scaling
- Support Vector Machines
- Recursive Feature Elimination
- Cross-validation
- Model evaluation
- Dimensionality reduction through feature selection

## Results

The model prints:
- Optimal number of selected features
- Accuracy score
- Precision, Recall, and F1-score
- Cross-validation performance graph
