# TWITTER-SENTIMENT-ANALYSIS
This project aims to perform sentiment analysis on a collection of tweets using machine learning techniques. The dataset used in this project is the Twitter Sentiment Analysis dataset from Kaggle, which contains over 1.6 million tweets labeled as either positive or negative. 

# Sentiment Analysis Project

## Overview

This project is a sentiment analysis project that uses the Twitter dataset from Kaggle to perform sentiment analysis on tweets. The dataset contains tweets from various sources, and each tweet is labeled as positive, negative, or neutral sentiment.

## Algorithms Used

To perform sentiment analysis, I have implemented three different algorithms: the RoBERTa model, the VADER model, and the Naive Bayes classifier.

- The RoBERTa model is a deep learning-based approach that uses a pre-trained language model to classify text into sentiment categories.
- The VADER model is a rule-based approach that uses a lexicon to assign sentiment scores to text data. It is specifically designed to handle sentiments expressed through social media text, such as emojis and slang.
- The Naive Bayes classifier is a classic machine learning-based approach that is commonly used for text classification tasks, including sentiment analysis.

## Preprocessing Text Data

To preprocess the text data, I have used the NLTK library in Python. I have performed several preprocessing steps, including tokenization, stop word removal, stemming, and lemmatization. These steps can help improve the accuracy of sentiment analysis models by preparing the text data for analysis.

## Evaluation

To evaluate the performance of the different algorithms, I have split the dataset into training and testing sets. I have trained the models on the training set and evaluated their performance on the testing set using accuracy as the metric.

## Libraries Used

I have used the following libraries in this project:

- pandas
- nltk
- scikit-learn

## Conclusion

Sentiment analysis is a powerful tool for analyzing the sentiment expressed in text data. This project demonstrates how different algorithms and preprocessing techniques can be used for sentiment analysis, and how the choice of algorithm can significantly impact the performance of the model.
