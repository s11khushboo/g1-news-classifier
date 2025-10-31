# **📰 NLP News Classifier using TF-IDF, GloVe embedding and XGBoost**

This project implements a news classifier that automatically categorizes news text into fraud and real using TF-IDF (Term Frequency–Inverse Document Frequency), GloVe embedding for feature extraction and XGBoost for classification.

---

## 🚀 Project Overview

The goal of this project is to build a robust machine learning model capable of classifying news articles fraud or real based on their textual content.

We use:

TF-IDF to convert raw text into numerical features.

XGBoost, a powerful gradient boosting algorithm, is used to perform the classification.



## 🧠 Key Features

Preprocessing of raw text (tokenization, stopword removal, etc.)

Vectorization using TF-IDF

Training and tuning an XGBoost classifier

Evaluation using precision, recall, F1-score, and confusion matrix

Support for new, unseen news article predictions


## 🧹 Data Preprocessing

The preprocessing pipeline includes:

Tokenize the words

Removing stopwords

TF-IDF vectorization for feature extraction

GloVe for word-level embeddings

## 🤖 Model Training

We train an XGBoost Classifier on the embedding matix

## 📈 Evaluation

The model is evaluated using standard classification metrics.
Typical metrics include:

Accuracy

Precision

Recall

F1-score

# 🔮 Making Predictions

You can predict the category of a new article using the saved model and vectorizer:

# 📊 Results
Accuracy: 0.9651588347240521


              precision    recall  f1-score   support

           0       0.97      0.96      0.97      3529
           1       0.96      0.97      0.96      3302

    accuracy                           0.97      6831


