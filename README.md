# credit-risk-assessment-using-classification
The project sets up a foundation for building a credit risk classification model, where the predictors (loan amount, duration, age, etc.) are used to estimate whether a customer’s credit risk is good or bad.  In short, it’s a data preprocessing and encoding exercise that prepares the dataset for machine learning classification tasks.
## 📌 Project Overview
This project explores the German Credit Data dataset to understand factors influencing credit risk. The goal is to prepare the dataset for machine learning classification tasks that predict whether a customer’s credit risk is good or bad.

## ⚙️ Workflow
Data Loading

Imported dataset from Excel using pandas.

## Data Cleaning

Normalized column names (lowercased, replaced spaces with underscores).

Renamed target column from risk to credit_risk.

## Feature Selection

Selected predictors such as:

credit_amount

duration

age

## Encoding

Transformed the target variable (credit_risk) into numerical form using LabelEncoder.

Mapped classes:

bad → 0

good → 1

## 🎯 Purpose
The notebook sets up a data preprocessing pipeline that prepares the dataset for classification models. This foundation enables further exploration with algorithms such as Logistic Regression, Decision Trees, or Random Forests to predict credit risk.
