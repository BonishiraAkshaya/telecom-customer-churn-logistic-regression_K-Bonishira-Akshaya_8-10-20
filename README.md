# Telecom Customer Churn Prediction using Logistic Regression

## Project Overview

This project predicts whether a telecom customer is likely to churn or stay using Logistic Regression.

The model uses customer information such as:

- Tenure
- Monthly Charges
- Total Charges

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Machine Learning Algorithm

Logistic Regression

The model classifies customers into two categories:

- 0 → Likely to Stay
- 1 → Likely to Churn

## Dataset

The dataset contains telecom customer information and their churn status.

## Model Performance

- Accuracy: 77.47%
- Correctly identified churn customers: 163
- Non-churn customers incorrectly classified as churn: 106

## Sample Prediction

For a customer with:

- Tenure: 12 months
- Monthly Charges: 70
- Total Charges: 840

The model predicted:

**Likely to Stay**

Probability of Churn: **45.89%**

## Business Analysis

It is better to wrongly flag a loyal customer as churn than to miss an actual churner, because missing a customer who is likely to leave can result in customer and revenue loss.

## Possible Improvement

More relevant customer features such as Contract, InternetService, PaymentMethod, and TechSupport can be included to improve the prediction.
