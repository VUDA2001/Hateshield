# 🛡️ Toxic Speech Classifier – HateShield

A machine learning-based NLP pipeline to detect toxic and hate speech in Filipino social media content. Built using TF-IDF vectorization, Naive Bayes classification, and K-Means clustering with t-SNE visualization.  

---

## Project Overview

Social media is filled with both constructive dialogue and harmful speech. This project tackles the growing need for automated toxic speech detection using machine learning, with a focus on Filipino text data.

We built a supervised classification model and evaluated its performance using real-world data containing toxic and non-toxic social media posts.

---

## Features

- ✅ Preprocessing: Tokenization, stopword removal, lemmatization
- ✅ TF-IDF vectorization with unigrams and bigrams
- ✅ Multinomial Naive Bayes classification
- ✅ Hyperparameter tuning with GridSearchCV
- ✅ Unsupervised K-Means clustering + t-SNE visualization
- ✅ WordClouds and performance visualizations
- ✅ Modular pipeline with reusable preprocessing functions

## Future Work
Integrate deep learning models (e.g., BERT, RoBERTa)

Add multilingual support

Deploy as a web API (FastAPI or Streamlit)

Implement real-time moderation dashboard

## Dataset Source

This project uses Filipino hate speech datasets sourced from:
https://github.com/imperialite/filipino-tiktok-hatespeech/tree/main
A collection of annotated hate speech and offensive language data from TikTok comments in Filipino.

The data includes training, testing, and validation sets labeled as toxic or non-toxic. Full credit to the original authors for providing high-quality annotated data.
