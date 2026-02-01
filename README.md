This project implements a spam email detection system using machine learning. The goal is to classify email messages as spam or not spam based on their text content.

The model uses TF-IDF feature extraction with unigrams and bigrams to convert text into numerical form. Logistic Regression is then trained on these features to learn common patterns found in spam and non-spam emails. Using n-grams helps the model capture meaningful word combinations such as promotional phrases and urgent messages.

The trained model achieves around 97 percent test accuracy, showing good performance on unseen data. It correctly identifies common spam patterns like promotional offers, scam alerts, and verification messages, while also handling normal personal and professional emails.

A simple Streamlit web application is included to test the model interactively. Users can paste an email message into the text box and instantly see whether it is classified as spam or not spam.

The project is implemented using Python, scikit-learn, TF-IDF Vectorizer, Logistic Regression, Streamlit, and Joblib. The trained model and vectorizer are saved and loaded to ensure consistent predictions during deployment.

This project can be used as a machine learning mini project, an NLP practice project, or a basic demonstration of text classification and model deployment.
