# sms-spam-classification-naive-bayes

Overview
This project focuses on detecting spam SMS messages using basic Natural Language Processing (NLP) techniques.
A Naive Bayes classifier is trained to classify messages as spam or ham (not spam).
The goal of this project is to demonstrate a simple and effective text classification pipeline suitable for junior-level data science and data analyst roles.
Dataset
SMS Spam Collection Dataset
Each message is labeled as:
spam
ham
Methods & Techniques
Text preprocessing
Bag of Words representation (CountVectorizer)
TF-IDF feature extraction (TfidfVectorizer)
Naive Bayes classifiers:
Multinomial Naive Bayes
Gaussian Naive Bayes (for comparison)
Model Workflow
Load and preprocess text data
Convert text into numerical features (CountVectorizer / TF-IDF)
Split data into training and test sets
Train Naive Bayes models
Evaluate performance using accuracy and classification metrics
Evaluation
Accuracy score
Classification report (precision, recall, F1-score)
Confusion matrix
Technologies Used
Python
pandas
scikit-learn
NumPy
Results
The model successfully identifies spam messages with reasonable accuracy, showing that Naive Bayes performs well for basic text classification tasks.
