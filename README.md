# project-parkinsons-disease-classification
This notebook uses the dataset from [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Parkinson%27s+Disease+Classification) and classification models to predict whether a patient has Parkinson's Disease, with a focus on modele improvement on Logistic Regression.

## Overview

### I. Data Preparation
- Load and Oberserve Data
- Data Preprocessing
- Min-Max Normalization
- Problem Definition

### II. Modeling

Each modeling section consists of **an brief intro, the algorithm, discussion on related topics, and application** on the dataset.

1. kNN
    - Non-parametric Models
    - Algorithm
2. Naive Bayes  
    - Bayes Classifier
    - Algorithm
    - Generative Model vs. Discriminative Model
3. Logistic Regression
    - Sigmoid Function
    - Maximum Likelihood Estimation
    - Algorithm
    - (Also see Appendix A & B for related topics)
4. Support Vector Machine
    - Convex Sets and Convex Hulls
    - Algorithm
    - Soft-Margin SVM
5. Kernel SVM
    - Kernel
    - Mercer's theorem
    - RBF
    - Algorithm
6. Decision Tree

### III. Model Improvement
- PCA
- Pipeline

### IV. Model Selection
- ROC Curve
- Change Threshold
- Classification Report

### V. Appendix
- Appendix A: Concepts for Logistic Regression
    - A1. Binary Classification
    - A2. Log Odds
    - A3. Linear Discriminant Analysis

- Appendix B: Linear Classifiers
    - B1. Definition
    - B2. Linear Separability
    - B3. Methods
