# CancerClassification-ML
Prepared by Derick Cazares, Melissa Morales, Renee Perez, and Feven Surafel

## Overview
The objective of this project is to utilize the Wisconsin Breast Cancer Diagnostic Dataset for predictive analysis to improve early detection and diagnosis of breast cancer. By leveraging machine learning techniques, we seek to develop a predictive model that can classify tumor samples as malignant or benign based on various features extracted from cell nuclei.

## Results
Machine Learning Logistic Regression Model (94% Accuracy)

Class B (Benign Diagnosis):

Precision is 0.95, meaning that when the model predicts a benign tumor, it is correct 95% of the time.
Recall is 0.95, meaning that 95% of all actual benign instances were correctly identified.
Class M (Malignant Diagnosis):

Precision is 0.93, meaning that when the model predicts a malignant tumor, it is correct 93% of the time.
Recall is 0.93, meaning that 93% of all actual malignant instances were correctly identified.

# Analysis

## Purpose
The purpose of this analysis is to create a machine learning model capable of accurately classifying breast cancer tumors based on features such as radius, texture, perimeter, and smoothness of cell nuclei.

## Data
The data used in this analysis comes from the Wisconsin Breast Cancer Diagnostic Dataset and includes the following:

569 samples
30 features representing characteristics of the tumor
Target labels: Benign (B) and Malignant (M)
Machine Learning Process

Data Preprocessing:

The dataset was cleaned and split into training and testing sets using train_test_split.
Model Training:

A Logistic Regression model was used due to its effectiveness in binary classification.
The model was trained on the training data and evaluated on the test data.

Evaluation Metrics:

The model’s performance was evaluated using metrics such as precision, recall, F1-score, and accuracy.
The confusion matrix and ROC curve were used to assess the model's predictions and trade-offs between true and false positives.

Correlation Analysis:

A correlation matrix was computed to analyze relationships between features, identifying highly correlated features.

## Summary

The Logistic Regression model performed well with an accuracy of 94%. It demonstrated high precision and recall for both benign and malignant tumor classifications, making it a strong candidate for this classification problem.

Best Model:

Logistic Regression achieved the best performance with balanced precision and recall for both tumor types.

Considerations:

Feature reduction based on the correlation analysis could further simplify the model.
Additional machine learning models, such as Random Forest or SVM, could be explored to see if further improvements in accuracy and precision are possible.

