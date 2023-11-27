# Twitter-Sentiment-Analysis

## Introduction

This project implements a machine learning pipeline to predict Twitter sentiments. It employs Linear Regression, Support Vector Machine, and Naive Bayes classifiers, with TF-IDF vectorization. Performance is evaluated using F1 score and accuracy.

## Problem Overview
Sentiment analysis on Twitter data helps in understanding public opinion. Our model classifies tweets as positive or negative using a labeled dataset for training and validation.

## Data Description
Two datasets are utilized:
- Development set: 224,597 labeled tweets.
- Evaluation set: 74,872 unlabeled tweets.

## Methodology
### Preprocessing
- Concatenation of datasets for uniform preprocessing.
- Dropping irrelevant features; focusing on 'text'.
- Text normalization (lowercasing, URL/emoticon/username removal, etc.).
- Lemmatization to deduce word roots.

### Model Training
- Splitting the development set into training and validation.
- Employing TF-IDF for feature extraction.
- Model selection: Logistic Regression, SVM, Naive Bayes.

## Proposed Approach
- Detailed preprocessing steps.
- Model selection rationale and implementation.
- Hyperparameter tuning results.

## Results
- Logistic Regression emerged as the best-performing model.
- Detailed performance metrics and analysis.
