# ML-Use-Cases

# 1. Rock vs Mine Prediction using Logistic Regression

## Problem

Predict whether an object is a rock or a mine based on sonar signal data.

## Model Used

Logistic Regression

## Dataset

* Sonar dataset
* Each sample contains numerical features representing sonar signals
* Output:

  * 0 → Rock
  * 1 → Mine

## Steps:

* Data loading using Pandas
* Data preprocessing and exploration
* Splitting features and labels
* Train-test split
* Model training using Logistic Regression
* Model evaluation using accuracy score
* Building a predictive system

## Learnings:

* Understanding binary classification problems
* Working with real-world numerical datasets
* End-to-end ML pipeline (data → training → prediction)
* How logistic regression works for classification tasks

## Key Insight:

* Logistic Regression is effective for binary classification problems with linearly separable data
* Model outputs probabilities which are converted into class labels


# 2. Diabetes Prediction using SVM

## Problem
Predict whether a person is diabetic based on medical attributes.

## Model Used
Support Vector Machine (SVM)

## Steps:
- Data preprocessing
- Feature scaling using StandardScaler
- Train-test split with stratification
- Model training using SVM
- Evaluation using accuracy

## Learnings:
- Importance of feature scaling for SVM
- Difference between linear and RBF kernel
- Understanding model generalization
