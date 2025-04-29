# Logistic-Regression

# Overview
This project implements a logistic regression model to classify breast tumors as malignant (M) or benign (B) based on diagnostic measurements. The model achieves high accuracy in predicting tumor malignancy and includes comprehensive evaluation metrics.

# Dataset
The dataset contains features computed from digitized images of fine needle aspirates (FNA) of breast masses. Key characteristics:

569 instances (212 malignant, 357 benign)
30 numeric features (mean, standard error, and worst values of 10 measurements)
Target variable: diagnosis (M = malignant, B = benign)

# Implementation Steps
1. Data Preparation
Load and inspect the dataset
Convert diagnosis to binary (M=1, B=0)
Drop non-feature columns (id, Unnamed: 32)
Split into training (80%) and test (20%) sets
Standardize features using StandardScaler

2. Model Training
Logistic regression with default parameters
Trained on standardized features

3. Evaluation Metrics
Confusion matrix
Classification report (precision, recall, F1-score)
ROC-AUC score
ROC curve visualization

4. Threshold Analysis
Precision-recall tradeoff at different thresholds
F1-score optimization
Visualization of performance metrics across thresholds

# Key Results
ROC-AUC score: 0.9974
Optimal threshold: 0.40
Best F1 score: 0.98
