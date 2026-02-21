# SMS Spam Filter using Python and NLP
This project implements a supervised SMS spam filtering system using NLP preprocessing and a frequency-based probabilistic classifier inspired by Naive Bayes.

## Client Background
Spam messages are a common problem in mobile communication. Companies need lightweight and explainable filters that can classify messages as spam or legitimate (ham). This project demonstrates a simple Natural Language Processing approach to spam detection.

## North Star Metrics
- Spam detection accuracy
- False positive rate (ham incorrectly labeled spam)
- Simplicity and interpretability

## Executive Summary
This project builds a simple SMS spam classifier using:
- Pandas for data handling
- NLTK for text preprocessing
- Python list comprehensions, loops, and conditionals
- Word frequency comparison for prediction

The program accepts a user-entered SMS message and predicts whether it is spam or ham.

## Data Structure
Dataset fields:
- `label`: spam or ham
- `sms`: message text

## Approach
1. Load dataset  
2. Preprocess text (lowercase, remove punctuation, remove stopwords)  
3. Count word occurrences in spam vs ham  
4. Build prediction function  
5. Accept user input and classify message  

## Tools Used
- Python
- Pandas
- NLTK

