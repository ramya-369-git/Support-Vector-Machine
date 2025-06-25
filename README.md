# Support Vector Machine (SVM) on Breast Cancer Dataset

## Overview

This project applies the Support Vector Machine (SVM) algorithm to classify tumors as malignant or benign using the Breast Cancer Wisconsin dataset. It demonstrates how SVM can be effectively used for binary classification problems in healthcare-related data.

## Objectives

- Apply supervised learning using the SVM algorithm.
- Predict whether a tumor is malignant or benign.
- Preprocess and scale data to improve model performance.
- Evaluate the model using standard classification metrics.

## Dataset

The Breast Cancer Wisconsin Diagnostic Dataset includes digitized features extracted from fine needle aspirate (FNA) of breast masses. It contains:

- 30 numeric features (e.g., radius, texture, smoothness)
- Target class:  
  - 0 = Malignant  
  - 1 = Benign

## Tools & Technologies

- Language: Python
- Libraries: scikit-learn, pandas, matplotlib, seaborn
- Environment: Jupyter Notebook

## Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## How to Use

1. Clone or download this repository.
2. Open the Jupyter Notebook file in a Python environment.
3. Run the cells to view data exploration, preprocessing, model training, and evaluation.

## Future Improvements

- Use Grid Search or Randomized Search for hyperparameter tuning.
- Try different SVM kernels (linear, RBF, polynomial).
- Compare SVM with other classifiers (e.g., Logistic Regression, Random Forest).
- Add feature selection or PCA for dimensionality reduction.

## License

This project is open-source and intended for educational and academic use.
