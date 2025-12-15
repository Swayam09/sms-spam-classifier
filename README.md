SMS Spam Classifier
Overview
This project demonstrates the application of machine learning and natural language processing techniques to classify SMS messages as spam or non-spam. The system focuses on text preprocessing, feature extraction, and supervised learning, and is deployed as an interactive web application using Streamlit.

Tech Stack
Python
Streamlit
scikit-learn
NLTK
Pandas
NumPy

Project Description
The classifier processes raw SMS text through multiple NLP steps including tokenization, stopword removal, and stemming. The cleaned text is transformed into numerical features using the TF-IDF technique. A Multinomial Naive Bayes model is then used to perform binary classification between spam and non-spam messages.
The project highlights practical experience with:
Text preprocessing pipelines
Feature engineering using TF-IDF
Model training and persistence using scikit-learn
Deploying ML models using Streamlit and GitHub

Project Structure
app.py – Streamlit application script
model.pkl – Trained machine learning model
vectorizer.pkl – TF-IDF vectorizer used for feature extraction
requirements.txt – Python dependencies for deployment

Deployment
The application is deployed on Streamlit Cloud directly from the GitHub repository. Dependency management is handled via the requirements.txt file, ensuring reproducible builds across environments.
