# Customer Churn Prediction using Machine Learning

## Overview

Customer churn is a critical business challenge for subscription-based companies, directly impacting customer retention and long-term revenue. This project develops a machine learning pipeline to predict whether a telecom customer is likely to churn using the IBM Telco Customer Churn dataset.

The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and interpretation. Multiple classification algorithms are benchmarked to identify the most effective model for churn prediction.

---

## Problem Statement

The objective of this project is to develop a binary classification model capable of identifying customers at risk of churning, enabling businesses to make data-driven customer retention decisions.

---

## Dataset

- **Dataset:** IBM Telco Customer Churn Dataset
- **Domain:** Telecommunications
- **Problem Type:** Binary Classification
- **Target Variable:** `Churn Value`
  - `0` → Customer Retained
  - `1` → Customer Churned

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn (SMOTE)
- Joblib

---

## Project Workflow

- Data Loading
- Data Cleaning & Missing Value Handling
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Categorical Encoding
- Feature Scaling
- Class Imbalance Handling using SMOTE
- Model Training
  - Logistic Regression
  - Random Forest
  - XGBoost
- Model Evaluation
- Feature Importance Analysis
- Model Serialization

---

## Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

---

## Repository Structure

```
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── README.md
├── requirements.txt
├── models/
└── images/
```


This project is intended for educational and portfolio purposes.
