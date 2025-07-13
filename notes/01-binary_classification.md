# 📘 Notebook Overview: MAGIC Gamma Telescope Classification
This Notebook prectices: **binary classification**
On the Dataset: **MAGIC Gamma Telescope** 
To classify: **gamma ray events** and **hadron events**

## Problem
**Supervised Learning - Binary Classification**
- Target : 'class' :
    - 1 : 'gamma'.
    - 0 : 'hedron'.

## Pre-Processing

- **Renamed Columns**: For readability.
- **Label Encoding**: Converted class labels (`'g'` and `'h'`) into binary (1 and 0).
- **Feature Scaling**: Used `StandardScaler` to normalize input features.
- **Oversampling**: Applied `RandomOverSampler` to balance the class distribution.

## EDA
Used **matplotlib** to visualize the distribution of each feature.

## Models Used
 - **k-Nearest Neighbors**: classifies a data point based on the majority label of its k nearest neighbors.
 - **Naive Bayes**: based on Bayes Theorem with the assumption of feature independence.
 - **Logistic Regression**: estimates the probability of a binary outcome using the logistic function.
 - **Support Vector Machine**: finds the optimal hyperplane that separates data into classes.
 - **Neural Network**: trained using backpropagation (multi-layer perceptron).

## Models Evaluation
Used **Classification Report** to evaluate:
 - **Precision**
 - **Accuracy**
 - **Recall**
 - **f1 score**
