# House Prices – Advanced Regression Techniques (Kaggle)

This repository contains my solution to the Kaggle **House Prices: Advanced Regression Techniques** competition.

## Approach
- Handled missing values using **median (numerical)** and **None (categorical)**
- Applied **one-hot encoding**
- Used **StandardScaler** for feature scaling
- Transformed target using **log1p**
- Trained a **Ridge Regression** model
- Inverse transformed predictions using **expm1**

## Why Ridge Regression?
Ridge regression handles multicollinearity and high-dimensional data effectively, which is common after one-hot encoding.

## Result
- **Public Leaderboard RMSE:** `0.14374`

## 🛠 Tools & Libraries
- Python
- pandas, numpy
- scikit-learn
- Google Colab

## How to Run
1. Download the notebook
2. Download dataset from Kaggle
3. Update dataset paths
4. Run all cells

## Competition Link
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques
