# -customer-churnprediction
# Customer Churn Prediction

## Description

This project focuses on predicting customer churn using machine learning.

The objective is to identify customers who are likely to leave a bank and provide interpretable insights that can support customer retention strategies.

## Objectives

- Analyze customer characteristics and churn behavior
- Perform exploratory data analysis
- Preprocess numerical and categorical variables
- Train several machine learning models
- Optimize the best-performing model
- Evaluate classification performance
- Identify important churn factors
- Segment customers according to churn risk

## Dataset

The project uses the Churn Modelling dataset containing approximately 10,000 customers.

The target variable is:

- `Exited`: customer churn indicator

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Optuna
- SHAP
- Joblib
- Jupyter Notebook

## Methodology

The project follows an end-to-end machine learning workflow:

1. Data loading
2. Data cleaning
3. Exploratory Data Analysis
4. Feature preprocessing
5. Train/test split
6. Model training
7. Cross-validation
8. Hyperparameter optimization
9. Threshold optimization
10. Model evaluation
11. Explainability
12. Customer risk segmentation

## Machine Learning Models

The following models were evaluated:

- Logistic Regression
- Random Forest
- XGBoost

XGBoost was further optimized using Optuna.

## 📈 Results

The optimized XGBoost model achieved:

- ROC-AUC: **0.8639**
- PR-AUC: **0.7153**

At a decision threshold of 0.60:

- Precision: **0.606**
- Recall: **0.654**
- F1-score: **0.629**
- Accuracy: **0.84**

