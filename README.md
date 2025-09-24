# IMDb-Sentiment-Classifier
A simple sentiment classifier using IMDb-style reviews
# IMDb Sentiment Classifier 

## Overview
This project is a simple sentiment analysis model built using IMDb-style movie reviews. It classifies reviews as either positive or negative using a Logistic Regression model.

## Dataset
- A manually created dataset of 50 reviews (25 positive, 25 negative)
- Reviews are written in the style of IMDb movie comments
- No external datasets were used

## Preprocessing
- Text data was vectorized using `CountVectorizer` from scikit-learn
- Stop words were removed to improve feature quality
- Data was split into training and test sets using `train_test_split`

## Model
- Algorithm: Logistic Regression
- Library: scikit-learn
- Accuracy achieved: **~70%** on the test set

## Files
- `sentiment_classifier.py`: Contains the full code for preprocessing, training, and evaluation
- `README.md`: This explanation file
