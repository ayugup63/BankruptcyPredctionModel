
**Project Overview**

This project focuses on predicting corporate bankruptcy using financial ratios and supervised machine learning techniques. The goal is to identify financially distressed companies early by analyzing profitability, liquidity, leverage, and debt-related indicators.

The dataset is highly imbalanced, making accuracy alone misleading. Therefore, the project emphasizes robust evaluation metrics and model interpretability.


**Dataset**

Source: Corporate bankruptcy dataset (financial statement data)

Size: 6,800+ companies

Features: 95 financial ratios

Target: Bankrupt? (0 = Non-Bankrupt, 1 = Bankrupt)

Dataset is highly imbalanced, making accuracy alone misleading. Therefore, the project emphasizes robust evaluation metrics and model interpretability.


**Methodology**

Data Cleaning & Preprocessing

Exploratory Data Analysis (EDA) : Target distribution analysis, Correlation analysis & heatmaps, Feature distributions (KDE plots), PCA for dimensionality reduction and visualization

Handling Class Imbalance

  Applied SMOTE (Synthetic Minority Oversampling Technique) on training data

Modeling & Evaluation

  Implemented and compared multiple classification models:
  
  K-Nearest Neighbors (K = 5, 10, 15)
  
  Artificial Neural Network (MLP with 4 hidden layers)
  
  Support Vector Machine (RBF Kernel)
  
  Random Forest
  
  XGBoost
  
  Gaussian Naïve Bayes


**Evaluation Metrics**

Models were evaluated using:

Precision, Recall, F1-score

ROC-AUC and PR-AUC

Confusion Matrix

Matthews Correlation Coefficient (MCC)


**Key Findings**

Tree-based models (Random Forest, XGBoost) achieved the best performance with ROC-AUC ≈ 0.96

ANN significantly reduced false positives compared to KNN

Feature selection and imbalance handling were critical for reliable predictions
