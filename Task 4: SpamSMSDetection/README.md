# Spam SMS Detection Using Machine Learning

## Overview

Spam messages are a common issue in digital communication, often containing unwanted advertisements, phishing attempts, or fraudulent content. This project focuses on building a machine learning model capable of automatically classifying SMS messages as either **Spam** or **Ham (Legitimate)**.

The model uses Natural Language Processing (NLP) techniques to transform text data into numerical features and applies a machine learning algorithm to perform the classification task.

---

## Objectives

* Analyze SMS text messages.
* Preprocess and clean textual data.
* Convert text into machine-readable features.
* Train a classification model to detect spam messages.
* Evaluate model performance using standard classification metrics.

---

## Dataset

The dataset consists of SMS messages labeled as:

* **Ham (0):** Legitimate messages
* **Spam (1):** Unwanted or promotional messages

The dataset contains thousands of real-world SMS samples used for training and testing the model.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* TF-IDF Vectorization
* Matplotlib
* Seaborn

---

## Project Workflow

### 1. Data Collection

The SMS dataset was loaded and inspected for structure, missing values, and class distribution.

### 2. Data Preprocessing

* Removed unnecessary columns.
* Renamed attributes for better readability.
* Converted categorical labels into numerical values.

### 3. Feature Extraction

Text messages were transformed into numerical vectors using **TF-IDF (Term Frequency–Inverse Document Frequency)**, allowing machine learning algorithms to process textual information effectively.

### 4. Model Training

A **Multinomial Naive Bayes** classifier was trained using the transformed SMS data.

### 5. Model Evaluation

The model was evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

### 6. Prediction

The trained model can classify new SMS messages as spam or legitimate.

---

## Results

The model achieved an accuracy of approximately **96.68%** on the testing dataset.

Performance metrics demonstrated strong classification capability, particularly in identifying legitimate messages while maintaining high precision for spam detection.

---

## Sample Prediction

Input Message:

Congratulations! You have won a free gift voucher. Click the link to claim now.

Output:

Spam

---

## Future Enhancements

* Experiment with advanced NLP techniques.
* Compare multiple machine learning algorithms.
* Deploy the model using Flask or Streamlit.
* Integrate the system into real-time messaging applications.

---

## Conclusion

This project demonstrates how Natural Language Processing and Machine Learning can be combined to build an effective spam detection system. By transforming text into numerical features and applying classification algorithms, the model successfully identifies unwanted SMS messages and helps improve communication security.

---

## Author

Sanket Kolhe

Machine Learning Internship Project – CODSOFT
