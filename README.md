

# 📰 Fake News Detection using NLP & Machine Learning

An end-to-end Natural Language Processing (NLP) based machine learning project that classifies news articles as **Fake** or **Real** using TF-IDF vectorization and Logistic Regression.

---

## 🚀 Project Overview

The goal of this project is to build a robust text classification model capable of detecting fake news articles based on textual features. The project implements a complete ML pipeline including data preprocessing, feature engineering, model training, evaluation, and inference.

---

## 🛠️ Tech Stack

* **Python**
* **Pandas, NumPy**
* **NLTK**
* **Scikit-learn**
* **TF-IDF Vectorizer**
* **Logistic Regression**

---

## 📂 Dataset

The dataset contains news articles with the following features:

* `id`
* `title`
* `author`
* `text`
* `label` (0 = Real, 1 = Fake)

---

## 🔄 Project Pipeline

Raw News Data
     ↓
Text Cleaning (Regex)
     ↓
Lowercasing
     ↓
Tokenization
     ↓
Stopword Removal
     ↓
Stemming (Porter Stemmer)
     ↓
TF-IDF Vectorization
     ↓
Train-Test Split (Stratified)
     ↓
Logistic Regression Model
     ↓
Prediction & Evaluation


---

## 🧠 Text Preprocessing

* Removed special characters and numbers using regular expressions
* Converted text to lowercase
* Removed English stopwords
* Applied Porter Stemming to reduce vocabulary size

---

## 📊 Model Training

* Used **TF-IDF Vectorization** to convert text into numerical feature vectors
* Applied **Logistic Regression** for classification
* Performed **Stratified Train-Test Split (80-20)** to maintain class balance

---

## 📈 Model Performance

* Achieved **98% Test Accuracy**
* Validated predictive capability on unseen news samples
* Ensured balanced class distribution using stratified sampling

---

## 🔮 Predictive System

The model can classify custom input news articles as:

* ✅ Real News
* ❌ Fake News


## 📌 Key Highlights

* End-to-end NLP pipeline implementation
* Feature engineering using TF-IDF
* High accuracy (98%) on unseen data
* Clean and modular ML workflow

---
