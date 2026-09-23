# SMS Spam Classifier - Streamlit App

## Project Overview

This project is a simple Streamlit application that predicts whether an SMS message is Ham or Spam.

The app uses the Logistic Regression model and TF-IDF vectorizer trained during the SMS Spam Classification project.

## How It Works

1. User enters an SMS message.
2. The message is converted into TF-IDF features.
3. The trained Logistic Regression model predicts the message.
4. The app displays Ham or Spam.

## Technologies Used

- Python
- Streamlit
- Scikit-learn
- TF-IDF
- Logistic Regression
- Jupyter Notebook

## Files

- `app.py` - Streamlit application
- `model.pkl` - Trained Logistic Regression model
- `vectorizer.pkl` - Saved TF-IDF vectorizer

## How to Run

Open Anaconda Prompt and go to the project folder:

```bash
cd "%USERPROFILE%\Desktop\SMS Spam Streamlit App"