# sms-spam-classification-naive-bayes


## Overview
This project focuses on detecting spam SMS messages using basic Natural Language Processing (NLP) techniques.
A Naive Bayes classifier is trained to classify messages as spam or ham (not spam).

The goal of this project is to demonstrate a simple and effective text classification pipeline suitable for junior-level data science and data analyst roles.

---

## Dataset
- SMS Spam Collection Dataset
- Each message is labeled as:
  - spam
  - ham

---

## Methods & Techniques
- Text preprocessing
- Bag of Words representation (CountVectorizer)
- TF-IDF feature extraction (TfidfVectorizer)
- Naive Bayes classifiers:
  - Multinomial Naive Bayes
  - Gaussian Naive Bayes (for comparison)

---

## Model Workflow
1. Load and preprocess text data
2. Convert text into numerical features (CountVectorizer / TF-IDF)
3. Split data into training and test sets
4. Train Naive Bayes models
5. Evaluate performance using classification metrics

---

## Evaluation
- Accuracy score
- Precision, Recall, F1-score
- Confusion matrix

---

## Technologies Used
- Python
- pandas
- NumPy
- scikit-learn

---

## Results
The model successfully identifies spam messages with reasonable accuracy, demonstrating that Naive Bayes is effective for basic text classification tasks.

---

