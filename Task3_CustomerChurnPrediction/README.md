# Customer Churn Prediction Using Machine Learning

## Overview

Customer retention is an important factor for business growth and long-term success. This project focuses on predicting whether a customer is likely to leave a bank based on demographic information, account details, and banking behavior.

By applying machine learning techniques, the project aims to identify customers who are at risk of churn, enabling businesses to take proactive measures to improve customer satisfaction and retention.

---

## Project Objectives

* Analyze customer data and understand churn behavior.
* Perform data preprocessing and feature preparation.
* Build a machine learning model for churn prediction.
* Evaluate model performance using classification metrics.
* Generate insights that support customer retention strategies.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

---

## Dataset Description

The dataset contains customer information including:

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Account Balance
* Number of Products
* Credit Card Status
* Active Membership Status
* Estimated Salary

Target Variable:

* **0** → Customer Retained
* **1** → Customer Churned

---

## Project Workflow

### Data Loading

The dataset was imported and examined to understand its structure and available attributes.

### Data Exploration

Customer information and churn distribution were analyzed to identify important trends and patterns.

### Data Preprocessing

Unnecessary columns were removed, categorical variables were encoded, and relevant features were prepared for model training.

### Model Development

A Logistic Regression model was implemented to classify customers based on their likelihood of leaving the bank.

### Handling Class Imbalance

Class balancing techniques were applied to improve the model's ability to identify churned customers.

### Model Evaluation

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

### Model Saving

The trained model was saved for future predictions and deployment purposes.

---

## Model Performance

| Metric                  | Value |
| ----------------------- | ----- |
| Accuracy                | 68%   |
| Precision (Churn Class) | 0.34  |
| Recall (Churn Class)    | 0.68  |
| F1-Score (Churn Class)  | 0.46  |

The balanced Logistic Regression model demonstrated a strong ability to identify customers likely to churn, making it useful for customer retention analysis.

---

## Key Findings

* Customer churn prediction is an imbalanced classification problem.
* Applying class balancing improved churn detection performance significantly.
* The model successfully identified a large proportion of churned customers.
* Predictive analytics can help organizations reduce customer attrition through early intervention.

---

## Future Enhancements

* Implement Random Forest and XGBoost models.
* Perform hyperparameter optimization.
* Apply advanced feature engineering techniques.
* Build an automated customer retention recommendation system.
* Deploy the model through a web application or API.

---

## Conclusion

This project demonstrates the practical use of machine learning for customer churn prediction. By analyzing customer attributes and behavioral patterns, the model can help businesses identify customers who may discontinue their services. Such insights can support strategic decision-making, improve customer engagement, and strengthen retention efforts.

---

## Author

**Sanket Kolhe**

Machine Learning Internship Project – CodSoft
