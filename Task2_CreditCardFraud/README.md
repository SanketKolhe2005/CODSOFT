# Credit Card Fraud Detection Using Machine Learning

## Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The objective is to build a classification model capable of identifying suspicious transactions and distinguishing them from legitimate ones. Fraud detection plays an important role in financial security, helping organizations reduce risks and prevent financial losses.

---

## Project Objectives

* Explore and analyze transaction data.
* Perform data preprocessing and feature selection.
* Train a machine learning model for fraud classification.
* Evaluate model performance using classification metrics.
* Identify fraudulent transactions with improved detection capability.

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

The dataset contains transaction records along with customer and merchant-related information. Each transaction is assigned a label:

* **0** → Legitimate Transaction
* **1** → Fraudulent Transaction

The dataset is highly imbalanced because fraudulent transactions represent only a small percentage of the total records.

---

## Project Workflow

### Data Loading

The training and testing datasets were imported and examined to understand their structure and available features.

### Exploratory Data Analysis

The dataset was analyzed to identify transaction patterns, class distribution, and potential challenges associated with fraud detection.

### Data Preparation

Relevant numerical features were selected and prepared for model training.

### Model Training

A Logistic Regression model with class balancing was implemented to improve the detection of fraudulent transactions.

### Model Evaluation

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

### Model Saving

The trained model was saved for future predictions and deployment.

---

## Model Performance

| Metric                  | Value |
| ----------------------- | ----- |
| Accuracy                | 95%   |
| Precision (Fraud Class) | 0.06  |
| Recall (Fraud Class)    | 0.75  |
| F1-Score (Fraud Class)  | 0.11  |

The model successfully identified a large proportion of fraudulent transactions. The recall score of 75% indicates that the model detected most fraud cases, which is important in fraud prevention systems.

---

## Key Findings

* The dataset showed a significant class imbalance between legitimate and fraudulent transactions.
* Applying class balancing improved the model's ability to detect fraud.
* Logistic Regression provided reliable fraud detection performance for this project.
* The model demonstrated the practical use of machine learning in financial transaction monitoring.

---

## Future Improvements

* Implement Random Forest and XGBoost models.
* Apply advanced feature engineering techniques.
* Perform hyperparameter optimization.
* Build a real-time fraud detection system.
* Deploy the model as a web application.

---

## Conclusion

A machine learning-based fraud detection system was developed using Logistic Regression. Through data analysis, preprocessing, and model evaluation, the project demonstrated how machine learning can assist in identifying suspicious financial transactions. The results highlight the potential of predictive analytics in improving transaction security and supporting fraud prevention efforts.

---

## Author

**Sanket Kolhe**

Machine Learning Internship Project – CodSoft
