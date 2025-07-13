# 📘 Notebook Overview: Seoul Bikes Count Regression
This Notebook prectices: **linear regression**
On the Dataset: **Seoul Bikes Count** 
To predict: **The number of bikes rentend**

## Problem
**Supervised Learning - Regression**
- Target : 'bikes count' : number of rented bikes

## Pre-Processing

- **Renamed Columns**: For readability.
- **Label Encoding**: Converted Functionning labels (`'Yes'` and `'No'`) into binary (1 and 0).
- **Feature Scaling**: Used `StandardScaler` to normalize input features.
- **Oversampling**: Applied `RandomOverSampler` to balance the class distribution.
- **Drop Irrelevent Columns**: `wind`, `visibility`, `functionning` ..

## EDA
Used **matplotlib** to visualize the distribution of each feature.

## Models Used
 - **Simple Linear Regression** (Only using 1 feature): using `LinearRegression()` from `sklearn`.
 - **Multiple Linear Regression** (All Features): using `LinearRegression()` from `sklearn`.
 - **Neural Network — Single Input (Temp)**: using normalization layer and one dense output layer without activation methode to get linear.
 - **Neural Network — Deep Network (Temp only)**
 - **Neural Network — All Features**

## Models Evaluation
Used :
 - **Mean Absolute Error**
 - **Mean Squared Error**
 - **R2 Score**