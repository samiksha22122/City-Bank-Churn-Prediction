# Churn Prediction Model

## Overview

This project focuses on building a **Churn Prediction Model** to predict whether a customer will leave (churn) or stay with a company. The model uses customer data to identify patterns and predict churn, enabling businesses to take proactive measures to retain customers.

---

## Features of the Project

- **Data Cleaning:** Handles missing values, outliers, and inconsistencies.
- **Feature Engineering:** Includes feature scaling, encoding categorical variables, and creating new meaningful features.
- **Exploratory Data Analysis (EDA):** Visualizes trends and relationships in the dataset.
- **Model Development:** Implements machine learning models such as Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting.
- **Evaluation:** Compares models using metrics like Accuracy, Precision, Recall, F1-score, and AUC-ROC.
- **Deployment:** Provides a framework for deploying the model in a production environment.

---

## Dataset

The dataset contains the following key features:

- **CustomerID:** Unique identifier for each customer.
- **CreditScore:** Customer's credit score.
- **Geography:** Country of residence.
- **Gender:** Gender of the customer.
- **Age:** Age of the customer.
- **Tenure:** Number of years with the company.
- **Balance:** Customer's account balance.
- **NumOfProducts:** Number of products the customer has.
- **HasCrCard:** Whether the customer has a credit card (1 = Yes, 0 = No).
- **IsActiveMember:** Whether the customer is an active member (1 = Yes, 0 = No).
- **EstimatedSalary:** Customer's estimated salary.
- **Exited:** Target variable (1 = Churned, 0 = Not Churned).

---

## Prerequisites

### Install Required Libraries
Ensure you have Python installed. Then install the required libraries:
```bash
pip install -r requirements.txt