# Customer Churn Prediction

## Project Overview

Customer Churn Prediction is a machine learning project that predicts whether a customer is likely to leave a company's service.

The project uses customer information such as tenure, contract type, monthly charges, internet service, payment method, and other customer-related features to predict churn.

## Objective

The main objective of this project is to:

- Analyze customer churn data
- Preprocess customer information
- Convert categorical data into numerical values
- Train a machine learning classification model
- Predict whether a customer will churn
- Evaluate the performance of the model
- Identify important features that contribute to churn prediction

## Dataset

The project uses a Telco Customer Churn dataset containing customer information and their churn status.

Some important features include:

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Contract
- Payment Method
- Monthly Charges
- Total Charges
- Churn

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Model

The project uses a:

### Random Forest Classifier

Random Forest is an ensemble machine learning algorithm that combines multiple decision trees to make predictions.

Since the target variable is customer churn (Yes/No), this project is a classification problem.

## Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Exploration
   ↓
Data Cleaning
   ↓
Categorical Data Encoding
   ↓
Feature and Target Separation
   ↓
Train-Test Split
   ↓
Random Forest Classifier
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Feature Importance
