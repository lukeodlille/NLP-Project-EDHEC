# IMDB Movie Review Sentiment Analysis

## Project Overview

This project analyzes sentiment in IMDB movie reviews using supervised machine learning techniques. The goal is to classify reviews as **positive** or **negative** based on textual content.

The project is split into two main parts:

- `cleaning.ipynb`: Preprocessing and cleaning raw review data.
- `imdb_reviews_study_FINAL.ipynb`: Model training, testing, and evaluation.

---

## Workflow Summary

1. **Data Cleaning**
   - Removed HTML tags, punctuation, and stopwords
   - Lowercased all text
   - Tokenized and lemmatized reviews

2. **Feature Engineering**
   - Used `CountVectorizer` / `TfidfVectorizer` for text-to-numeric transformation
   - Created training and testing datasets

3. **Model Training & Evaluation**
   - Tried multiple classifiers (e.g., Logistic Regression, Naive Bayes)
   - Evaluated using accuracy, precision, recall, F1-score
   - Chose best-performing model based on validation results


