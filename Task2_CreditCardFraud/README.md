# Credit Card Fraud Detection Using Machine Learning

## Overview

This project presents a machine learning approach for identifying fraudulent credit card transactions. The objective is to analyze transaction data and build a classification model capable of distinguishing between legitimate and fraudulent activities.

Fraud detection is a critical challenge in the financial sector due to the large volume of daily transactions and the relatively small number of fraudulent cases. This project demonstrates how machine learning can be applied to address this problem effectively.

---

## Project Objectives

* Analyze transaction data to understand fraud patterns.
* Perform data preprocessing and exploratory data analysis.
* Train a machine learning model for fraud classification.
* Evaluate model performance using standard classification metrics.
* Identify the effectiveness of the model in detecting fraudulent transactions.

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

## Dataset Information

The project uses transaction records containing customer, merchant, and transaction-related information. Each transaction is labeled as either:

* **0** → Legitimate Transaction
* **1** → Fraudulent Transaction

The dataset is highly imbalanced, making fraud detection a challenging classification problem.

---

## Project Workflow

### 1. Data Loading

Training and testing datasets were imported and inspected to understand their structure.

### 2. Data Exploration

Basic statistics, dataset information, and class distribution were analyzed to gain insights into the data.

### 3. Data Preprocessing

Relevant features were selected and prepared for model training.

### 4. Model Development

A Logistic Regression model was implemented to classify transactions as fraudulent or legitimate.

### 5. Model Evaluation

The trained model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

### 6. Model Saving

The final trained model was saved for future use and deployment.

---

## Results

The model demonstrated its ability to identify fraudulent transactions despite the imbalanced nature of the dataset. Class balancing techniques were applied to improve fraud detection performance and increase the model's sensitivity to fraudulent cases.

---

## Conclusion

This project demonstrates the practical application of machine learning in financial fraud detection. By analyzing transaction patterns and training a classification model, the system can assist in identifying suspicious activities and reducing potential financial risks. Further improvements can be achieved through advanced algorithms, feature engineering, and hyperparameter optimization.

---

## Future Enhancements

* Implement Random Forest and XGBoost models
* Perform hyperparameter tuning
* Apply advanced feature engineering techniques
* Develop a real-time fraud detection system
* Deploy the model using a web application framework

---

## Author

**Sanket Kolhe**

Machine Learning Intern Project – CodSoft
