# Spam SMS Detection Using Machine Learning

## Project Overview

Spam messages are a major challenge in digital communication, often containing advertisements, scams, or malicious links. This project aims to build a machine learning model that can automatically classify SMS messages as either **Spam** or **Ham (Legitimate)**.

The model uses Natural Language Processing (NLP) techniques to transform text data into numerical features and applies the Multinomial Naive Bayes algorithm for classification.

---

## Objectives

* Identify spam and legitimate SMS messages.
* Apply text preprocessing techniques.
* Convert text into numerical features using TF-IDF.
* Train and evaluate a machine learning model.
* Predict the category of new SMS messages.

---

## Dataset Information

The dataset contains **5,572 SMS messages** labeled as:

* **Ham (Legitimate):** 4,825 messages
* **Spam:** 747 messages

After preprocessing, the dataset was used to train and test the classification model.

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

### 1. Data Loading

The SMS dataset was imported and examined to understand its structure and content.

### 2. Data Cleaning

* Removed unnecessary columns.
* Renamed columns for clarity.
* Converted labels into numerical values:

  * Ham → 0
  * Spam → 1

### 3. Feature Extraction

TF-IDF (Term Frequency–Inverse Document Frequency) was used to convert SMS text into numerical vectors suitable for machine learning.

### 4. Train-Test Split

The dataset was divided into training and testing sets to evaluate model performance effectively.

### 5. Model Training

A **Multinomial Naive Bayes** classifier was trained using the transformed text data.

### 6. Model Evaluation

The trained model was evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

### 7. Prediction

The model can classify new SMS messages as Spam or Ham.

---

## Results

### Model Accuracy

**Accuracy: 96.68%**

### Classification Report

| Metric    | Ham (0) | Spam (1) |
| --------- | ------- | -------- |
| Precision | 0.96    | 1.00     |
| Recall    | 1.00    | 0.75     |
| F1-Score  | 0.98    | 0.86     |

### Confusion Matrix

| Actual / Predicted | Ham | Spam |
| ------------------ | --- | ---- |
| Ham                | 965 | 0    |
| Spam               | 37  | 113  |

### Key Observations

* The model achieved high overall accuracy.
* All messages predicted as spam were correctly classified.
* The model successfully identified most spam messages while maintaining excellent performance on legitimate messages.

---

## Sample Prediction

### Input Message

Congratulations! You have won a free iPhone. Claim now.

### Output

Spam Message

---

## Project Structure

```text
Spam_SMS_Detection/
│
├── Spam_SMS_Detection.ipynb
├── spam_model.pkl
├── tfidf_vectorizer.pkl
├── README.md
├── confusion_matrix.png
└── spam.csv
```

---

## Future Improvements

* Experiment with Support Vector Machines (SVM).
* Use advanced NLP techniques such as Word Embeddings.
* Deploy the model as a web application using Flask or Streamlit.
* Improve spam recall through hyperparameter tuning.

---

## Conclusion

This project demonstrates the practical application of Natural Language Processing and Machine Learning for SMS spam filtering. By combining TF-IDF feature extraction with the Multinomial Naive Bayes algorithm, the model achieved an accuracy of 96.68% and effectively classified SMS messages into spam and legitimate categories.

---

## Author

**Sanket Kolhe**

Machine Learning Internship Project – CODSOFT
