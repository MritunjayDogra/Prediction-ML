# Customer Chur Preciction

## Overview:
This project focuses on analyzing customer behavior and predicting whether a customer is likely to churn (leave a service). The goal is to help businesses identify at-risk customers and take proactive steps to retain them.

## Objective:
1. Perform Data Cleaning
2. Conduct EDA (Exploratiry Data analysis)
3. Identify Key Factors influencing churn
4. Build and Evaluate machine learning models

## Dataset:
Telco Customer Churn.csv

## Project Workflow

### Data Cleaning
1. Handled missing values
2. Converted data types
3. Removed irrelevant columns

### Exploratory Data Analysis (EDA)
1. Analyzed churn distribution
2. Studied relationships between churn and features like:
   ```
   Contract type
   Monthly charges
   Tenure
### Feature Engineering
1. Encoded categorical variables
2. Scaled numerical features

### Model Building
Implemented multiple machine learning models:
1. Logistic Regression
2. Decision Tree
3. Random Forest

### Model Evaluation
1. Accuracy Score
2. Confusion Matrix
3. Precision, Recall, F1-score

## Results
`Logistic Regression` achieved the best performance
Model accuracy: ~81.61%

## Key Insights
1. Customers with month-to-month contracts are more likely to churn
2. Higher monthly charges increase churn probability
3. Customers with low tenure are at higher risk
