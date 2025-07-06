# Customer-churn-analysis
This project aims to predict customer churn using machine learning techniques. The notebook includes data preprocessing, exploratory data analysis (EDA), feature engineering, and model training using several classification algorithms.

## 1. Telco Churn Analysis

### 🔎 Project Overview

This project focused on analyzing and predicting customer churn in the telecommunications industry using a machine learning approach. The dataset used contains customer account information and service details, including whether or not the customer has churned.

The notebook walks through a full machine learning pipeline — from data loading and cleaning to training and evaluating classification models — to predict churn effectively.

### 🚀 Key Steps

- **Data Loading & Exploration**: Dataset used — `WA_Fn-UseC_-Telco-Customer-Churn.csv`. Includes inspection of column types, missing values, and churn class balance.
- **EDA**: Includes count plots (e.g., gender, partner), boxplots (churn vs. monthly charges), and visual breakdowns by internet service and contract type.
- **Data Cleaning**: Converted `TotalCharges` to numeric, handled missing values, and removed invalid rows.
- **Feature Engineering**: Used `LabelEncoder` for categorical variables and combined features into a clean dataset.
- **Handling Imbalanced Data**: Applied **SMOTE** (Synthetic Minority Over-sampling Technique).
- **Model Building**: Trained multiple classifiers: **Logistic Regression**, **Decision Tree**, **Random Forest**, **Gradient Boosting**, and **XGBoost**.
- **Model Evaluation**: Evaluated using **Accuracy**, **Recall**, and **F1 Score**.

### 📊 Techniques Used

- **Exploratory Data Analysis (EDA)**
- **Data Cleaning & Preprocessing**
- **Feature Encoding & Scaling**
- **Model Training & Evaluation**
  - Logistic Regression
  - Random Forest
  - XGBoost
- **Accuracy, Precision, Recall, F1-Score**

## 📦 Requirements

Make sure to have the following libraries installed:

```bash
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
```

---
