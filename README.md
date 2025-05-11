# fake-news-prediction-using-AI-ML
## Overview:

Fake news prediction is the process of identifying and classifying news content as either real or fake using machine learning (ML) techniques. With the rise of social media and online news platforms, misinformation and disinformation can spread quickly and influence public opinion, making automatic fake news detection an essential tool in modern digital communication.

## description 
Fake news refers to news articles that are intentionally and verifiably false, designed to mislead readers. The key challenge in detecting fake news lies in analyzing the content of an article or post to determine its authenticity based on patterns, linguistic features, and historical data.

Machine learning models can be trained on labeled datasets (real and fake news articles) to learn patterns in text and make predictions on new, unseen data. This process involves natural language processing (NLP), text analysis, and classification techniques.

## architecture of the project
#### 1-data collection from the various sources like www , kaggle or any real world problems 
#### 2-data preprocessing 
Data preprocessing is a crucial step in building a machine learning model, especially for natural language tasks like fake news detection. Raw text data is noisy and unstructured, so it needs to be cleaned and transformed into a format suitable for modeling.
*Loading the Dataset
*Handling Missing Values
*Combining Text Features (if needed)
*Text Cleaning
*Text Vectorization
*Encoding Labels
*Train-Test Split
##### these all are done in above project 
#### 3- model building and model selection 
In this i choosen a LogisticRegression model because logistic regression is best for binary labelled data prediction 
#### logistic regression :
Logistic Regression is a widely used classification algorithm that works well for binary classification tasks like identifying whether a news article is fake or real.

#### 4- And finally model evaluation 
for model evaluation i used accuracy score and it scored about 98% almost 

#### 5- prediction also getting good score is almost 97% 
