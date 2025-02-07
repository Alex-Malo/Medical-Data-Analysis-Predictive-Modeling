# Medical-Data-Analysis-Predictive-Modeling
## Overview

This project focuses on analyzing medical patient data, specifically to derive an age variable and apply machine learning techniques for predictive modeling. The goal is to explore the relationship between age and patient outcomes, including mortality rate and length of stay (LOS) in hospitals.

## Dataset

The project uses multiple datasets:

- mimic_train.csv: The main dataset containing patient records.

- MIMIC_diagnoses.csv: Additional diagnosis data.

- Xtest.csv: The test dataset.

## Key Features

### Data Preprocessing:

- Standardizing and merging datasets.

- Extracting age from Date of Birth (DOB).

- Handling missing values using KNN Imputation and Simple Imputation.

### Machine Learning Models:

- Regression Models: Decision Tree, AdaBoost, Random Forest, Gradient Boosting, Stacking Regressor.

- Classification Models: K-Nearest Neighbors (KNN).

- Performance Evaluation: Accuracy, ROC AUC, RMSE scores.

## Libraries Used

- pandas, numpy, seaborn, matplotlib

- scikit-learn, lightgbm
