# Machine Learning Projects Portfolio

## Developer
Semere Brhane


## Overview
This repository contains multiple machine learning projects implemented using Python and scikit-learn. Each project focuses on different datasets and classification algorithms.


## Projects Included

### 1. Seed Classification (SVM)
- Dataset: Seed_Data.csv
- Algorithm: Support Vector Machine (SVM)
- Techniques:
  - Data preprocessing
  - Feature scaling
  - GridSearchCV hyperparameter tuning
  - Model evaluation using accuracy score


### 2. Breast Cancer Classification (Logistic Regression)
- Dataset: Built-in sklearn breast cancer dataset
- Algorithm: Logistic Regression
- Techniques:
  - Data standardization
  - Train-test split
  - Model training and prediction
  - Confusion matrix evaluation


### 3. Titanic Survival Prediction (SVM)
- Dataset: train.csv (Titanic dataset)
- Algorithm: Support Vector Machine (SVM)
- Techniques:
  - Data preprocessing (removal of unnecessary columns)
  - Handling missing values (Age, Embarked)
  - Feature encoding (Sex, Embarked)
  - Feature scaling using StandardScaler
  - Train-test split
- Model:
  - SVC with polynomial kernel
  - C = 13, degree = 2, coef0 = 3
- Evaluation:
  - Accuracy: ~82.7%
  - Confusion matrix and classification report used


### 4. Breast Cancer Classification (Decision Tree)
- Dataset: Built-in sklearn breast cancer dataset
- Algorithm: Decision Tree Classifier
- Techniques:
  - Data loading from sklearn dataset
  - Feature name cleaning
  - Train-test split
  - Decision tree training
  - Cost complexity pruning (ccp_alpha)
  - Cross-validation to select best alpha

- Model Optimization:
  - Used pruning to reduce overfitting
  - Selected best alpha using cross-validation

- Final Model Performance:
  - Initial Accuracy: ~94.7%
  - Pruned Model Accuracy: ~95.6%


## Libraries Used
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn


## Purpose
To demonstrate understanding of:
- Supervised learning
- Classification algorithms (SVM, Logistic Regression, Decision Tree)
- Data preprocessing
- Feature engineering
- Model evaluation
- Model optimization (pruning & cross-validation)


## Author
Semere Brhane
