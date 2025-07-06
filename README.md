# Customer-churn-analysis
This project aims to predict customer churn using machine learning techniques. The notebook includes data preprocessing, exploratory data analysis (EDA), feature engineering, and model training using several classification algorithms.

## 1. Telco Churn Analysis

### Project Overview

This project focused on analyzing and predicting customer churn in the telecommunications industry using a machine learning approach. The dataset used contains customer account information and service details, including whether or not the customer has churned.

The notebook walks through a full machine learning pipeline — from data loading and cleaning to training and evaluating classification models — to predict churn effectively.

#### Key Steps Include:

**Data Loading & Exploration**

Dataset: WA_Fn-UseC_-Telco-Customer-Churn.csv

Displays head of the data, data types, missing values, and churn class balance.

**Exploratory Data Analysis (EDA)**

Visualizations include:

Count plots for categorical variables (e.g., gender, partner, dependents).

Boxplot comparing churn vs. monthly charges.

Count plots segmented by churn and service types (e.g., internet service, contract type).

**Data Cleaning**

Converted TotalCharges from string to numeric, handling errors and missing values.

Removed rows with missing values.

**Feature Engineering**

Categorical variables encoded using LabelEncoder.

Combined numerical and categorical features into a single clean DataFrame.

**Handling Imbalanced Data**

Applied SMOTE (Synthetic Minority Over-sampling Technique) to balance the training data.

**Model Building**

Trained multiple classification models:

Logistic Regression

Decision Tree

Random Forest

Gradient Boosting

XGBoost

**Model Evaluation**

Evaluation metrics used:

Accuracy

Recall

F1 Score
