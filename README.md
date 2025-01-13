# Twitter Sentiment Analysis

This project performs **sentiment analysis on Twitter data**, identifying whether tweets are positive or negative. It employs machine learning techniques and natural language processing (NLP) methods to process and classify the data effectively.

---

## Introduction

This project leverages sentiment analysis to understand user opinions and trends on social media. By analyzing tweet data, it can assist businesses, organizations, and researchers in decision-making processes.

---

## Dataset

- **Source:** [Sentiment140 Dataset](https://www.kaggle.com/kazanova/sentiment140)
- **Contents:** Tweets labeled with sentiment polarity:
  - `0`: Negative sentiment
  - `4`: Positive sentiment (converted to `1` in preprocessing)
- **Format:** CSV file with text and sentiment labels.

---

## Features

- **Preprocessing:** 
  - Converting sentiment labels (`4` to `1` for positive sentiment).
  - Removing special characters, URLs, and mentions.
  - Stemming to reduce words to their root forms.
- **Feature Engineering:** 
  - TF-IDF (Term Frequency-Inverse Document Frequency) representation.
- **Modeling:**
  - Logistic Regression for sentiment classification.
- **Evaluation:**
  - Accuracy score.

---

## Setup

1. Install necessary libraries:
   ```bash
   pip install kaggle numpy pandas nltk scikit-learn

2. Configure Kaggle API:
   Upload your kaggle.json file:
   ```bash
   mkdir -p ~/.kaggle
  cp kaggle.json ~/.kaggle/
  chmod 600 ~/.kaggle/kaggle.json

---
## Technologies Used
Programming Language: Python
Libraries:
numpy, pandas for data manipulation
nltk for text preprocessing
scikit-learn for machine learning
kaggle for dataset management

   
