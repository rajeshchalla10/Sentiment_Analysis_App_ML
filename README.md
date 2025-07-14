# Text Sentiment Analysis with Bag of Words and TF-IDF
## Introduction

This project implements a text sentiment analysis classifier using Python, leveraging two popular text vectorization techniques: Bag of Words (BoW) and TF-IDF (Term Frequency-Inverse Document Frequency). Sentiment analysis is crucial for understanding the emotional tone of text, which has widespread applications, such as analyzing customer feedback and monitoring brand reputation.

## Features

- Text Preprocessing: Includes steps for cleaning and preparing raw text data for analysis.
- Bag of Words (BoW): Converts text into numerical vectors by representing documents as bags of words, focusing on word frequencies.
- TF-IDF (Term Frequency-Inverse Document Frequency): Enhances the BoW model by considering the importance of words based on their frequency within a document and across the entire corpus. Words that are common in a document but rare across the corpus receive higher weight.
- Machine Learning Model: Trains a classifier (e.g., Naive Bayes or Logistic Regression) on the vectorized data to predict sentiment (positive, negative, or neutral).
- Evaluation Metrics: Provides evaluation metrics like accuracy and classification reports to assess model performance.

## Prerequisites

- Python 3.6 or higher.
- Required Python libraries: nltk, scikit-learn, pandas, numpy (install using pip).
