# Hate Speech Detection

This project aims to detect hate speech in textual data using machine learning techniques. It involves preprocessing a labeled dataset, extracting features, and training a classification model to identify whether a piece of text contains hate speech or not.

## 📁 Project Structure

HateSpeechDetection/
├── hatespeech.ipynb # Jupyter Notebook with EDA, preprocessing, model training & evaluation
├── train.csv # Dataset with text and corresponding labels
└── .git/ # Git version control folder

markdown
Copy
Edit

## 📌 Features

- Exploratory Data Analysis (EDA) on the dataset
- Text preprocessing using NLP techniques
- Feature extraction using TF-IDF
- Model training using classification algorithms (e.g., Logistic Regression, SVM)
- Evaluation using metrics like accuracy, precision, recall, F1-score

## 📦 Requirements

Install the required libraries before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk
