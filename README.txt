Loan Approval Prediction

Project Overview
This project predicts loan approval status using various machine learning classifiers. It evaluates model performance and explores the impact of dimensionality reduction with Principal Component Analysis (PCA) on classification accuracy.

Key Features
Classifiers Implemented:
Linear Discriminant Analysis (LDA)
Decision Tree
k-Nearest Neighbors (kNN)
Support Vector Machine (SVM)

Dimensionality Reduction:
Principal Component Analysis (PCA) to reduce feature dimensions for kNN and SVM classifiers.
Performance Metrics:
Type 1 Error Rate: Approved loans misclassified as denied.
Type 2 Error Rate: Denied loans misclassified as approved.

Dataset
TrainingData.csv: Contains 900 samples with 27 features and labels (LoanApproved).
TestingData.csv: Contains 400 samples for evaluation.

Key Modules
Data Loading and Preprocessing:
Loads and cleans data from CSV files.
Scales features for SVM and PCA models.

Classifiers:
Implements LDA, Decision Tree, kNN, and SVM classifiers.
Includes grid search for optimal k values in kNN.

PCA Analysis:
Reduces dimensions to 5, 10, and 15 components.
Retrains kNN and SVM on reduced features.

Visualization:
Plots error rates and PCA performance comparisons.

Results
Error rates (Type 1 and Type 2) for each classifier.
Impact of PCA on model performance for kNN and SVM.

Requirements
Python 3.x
Libraries:
pandas, numpy, scikit-learn, matplotlib