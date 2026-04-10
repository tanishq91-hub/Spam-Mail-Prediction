# 📧 Spam Email Detection System 🚀

## 🔍 Overview

This project implements a **machine learning–based spam email detection system** designed to classify email messages as either **spam** or **legitimate (ham)** based on their textual content.

The objective is to build a reliable and efficient text classification pipeline that can automatically detect unwanted or malicious emails using natural language processing (NLP) techniques.

---

## ⚙️ Model Architecture

### 🧠 Feature Engineering

The system uses **TF-IDF (Term Frequency–Inverse Document Frequency)** vectorization with:

* **Unigrams** (single words)
* **Bigrams** (two-word combinations)

This approach converts raw text into a numerical representation while preserving contextual information. The inclusion of n-grams allows the model to capture meaningful patterns such as:

* “limited offer”
* “verify account”
* “click here”

---

### 📊 Classification Model

A **Logistic Regression** classifier is trained on the extracted features to distinguish between spam and non-spam emails.

* Efficient and lightweight model ⚡
* Performs well on high-dimensional sparse data
* Suitable for real-time inference scenarios

---

## 📈 Performance

The trained model achieves approximately:

* **✅ 97% accuracy on the test dataset**

This indicates strong generalization capability and robustness on unseen data. The model effectively identifies:

* 📢 Promotional spam
* ⚠️ Phishing and scam messages
* 🔐 Verification and urgency-based emails

At the same time, it maintains reliable performance on:

* 📩 Personal emails
* 💼 Professional communications

---

## 🌐 Interactive Web Application

A simple and user-friendly **Streamlit web application** is included for real-time testing.

### Features:

* 📝 Input any email text
* ⚡ Instant classification (Spam / Not Spam)
* 🎯 Lightweight and easy to deploy

This makes the project suitable for demonstrations and quick experimentation.

---

## 🛠️ Tech Stack

* **Python** 🐍
* **scikit-learn** (model training & evaluation)
* **TF-IDF Vectorizer** (feature extraction)
* **Logistic Regression** (classification)
* **Streamlit** (web interface)
* **Joblib** (model serialization)

---

## 💾 Model Persistence

The trained model and vectorizer are saved using **Joblib**, ensuring:

* 🔁 Consistent predictions during deployment
* ⚡ Fast loading and inference
* 📦 Easy portability

---

## 🎯 Use Cases

This project is ideal for:

* 📚 Machine Learning mini projects
* 🧪 NLP practice and experimentation
* 🧩 Understanding end-to-end ML pipelines
* 🚀 Basic model deployment demonstrations

---

## 📌 Summary

This project demonstrates a complete workflow:

1. Text preprocessing & feature extraction
2. Model training & evaluation
3. Deployment via a web interface

It provides a strong foundation for building more advanced **text classification systems** and real-world NLP applications.

---
