# Sentiment Analysis of Apple Across Social Media

## Overview
This project performs sentiment analysis on text data related to Apple products and services using machine learning techniques.

The objective is to classify user opinions into:
- Positive
- Negative
- Neutral

---

## Features
- Data collected from multiple platforms (social media & product reviews)
- Data preprocessing (cleaning, stopword removal, stemming)
- Exploratory Data Analysis (EDA)
- Feature extraction using TF-IDF
- Multiple machine learning models
- Model comparison and selection
- Prediction system for new text input

---

## Models Used
- Multinomial Naive Bayes  
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  

---

## Results
- Best Model: **Decision Tree**
- Accuracy: **~85%**
- Balanced dataset improved model performance

---

## Example Prediction

```python
predict_sentiment("This product is amazing")
# Output: Positive
