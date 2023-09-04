# Twitter Disaster Prediction

## Overview
This machine learning project is designed to predict whether tweets are about real disasters or not. With the increasing use of social media, particularly Twitter, for real-time updates on events and emergencies, this project can be valuable for disaster relief organizations and news agencies to monitor Twitter more effectively.

## Table of Contents
- [Introduction](#introduction)
- [Usage](#usage)
- [Installation](#installation)
- [Data Preprocessing](#data-preprocessing)
- [Machine Learning Model](#machine-learning-model)
- [Results](#results)

## Introduction
Twitter has become a valuable platform for people to report and discuss emergencies. However, not all tweets are related to real disasters, making it crucial to distinguish between them. This project employs natural language processing and machine learning techniques to classify tweets as either disaster-related or not.

## Usage
To use this project, follow these steps:

1. **Clone the Repository**
  git clone https://github.com/your-username/twitter-disaster-prediction.git

2. **Install Dependencies**
   pip install pandas numpy scikit-learn nltk

3. **Download NLTK Resources**
Before running the code, make sure to download the NLTK resources by executing the following in a Python shell:
```python
import nltk
nltk.download('stopwords')
```

#Data Preprocessing
Data preprocessing is a crucial step in this project. It involves text cleaning, lowercasing, tokenization, stop word removal, and stemming. This ensures that the text data is in a suitable format for the machine learning model.

#Machine Learning Model
We used a Support Vector Machine (SVM) with the Radial Basis Function (RBF) kernel to build our classification model. The model achieved an accuracy of 80% on the test data.

#Results
The confusion matrix and accuracy score for the model's predictions on the test data are displayed below:
```
Confusion Matrix:
[[True Positives  False Negatives]
 [False Positives True Negatives]]

Accuracy: 0.80
```
