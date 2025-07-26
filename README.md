# Fake-News
News Article Classification (Fake/Real)
Fake News Detector
A machine learning application for classifying news articles as Fake or Real using Natural Language Processing and Logistic Regression. The project features a simple, interactive web interface built with Streamlit.

📖 Introduction
Fake news is a widespread problem in today’s digital age. This project aims to help users identify misleading news articles by leveraging machine learning techniques. Users can input an article and instantly receive a prediction on its authenticity.

🚀 Features
Cleans and processes raw news text

Extracts features using TF-IDF vectorization

Classifies articles with a trained Logistic Regression model

User-friendly web app powered by Streamlit

🛠 Tools & Technologies
Language: Python

Libraries: pandas, numpy, scikit-learn, joblib, streamlit, re, string

Interface: Streamlit web app

🗂 Project Structure
text
fake-news-detector/
│
├── app.py               # Streamlit web app
├── vectorizer.jb        # Saved TF-IDF vectorizer
├── lr_model.jb          # Saved Logistic Regression model
├── requirements.txt     # Python dependencies
├── README.md            # Project documentation
├── True.csv             # (Dataset) Real news articles
└── Fake.csv             # (Dataset) Fake news articles
⚙️ How to Run
Clone this repository

🔑 Steps in Building the Project
Data Preparation: Combined real and fake news datasets, labeled them, and removed irrelevant columns.

Preprocessing: Cleaned text to remove noise, URLs, punctuation, and digits.

Feature Extraction: Applied TF-IDF vectorization to convert text to numerical features.

Model Training: Trained a Logistic Regression model and evaluated performance.

Saving Artifacts: Used joblib to save the model (lr_model.jb) and vectorizer (vectorizer.jb).

Deployment: Built a Streamlit app for real-time predictions.

📈 Results
Achieved high accuracy in distinguishing between real and fake news.

Interactive interface for quick, user-friendly predictions.
