# Sentiment-Analysis-Project

## Project Description

This is a sentiment analysis project that uses a dataset of ~8,000 tweets from X (formerly Twitter). The dataset is stratified for training and for testing. The goal of this project is to create a model that can predict whether a tweet is positive or negative. The model is created using several modified logisitc regressions. Incremental improvements to the model are proposed, programmed, and analyzed to determine improvments in time/space efficiency, accuracy, variance, etc. Additionally, cross-validation using GridSearchCV is done in order to further understand any overfitting. The model is then used to predict whether a review is positive or negative.

## What is Sentiment Analysis?

Sentiment analysis is the process of computationally identifying and categorizing opinions expressed in a piece of text, especially in order to determine whether the writer's attitude towards a particular topic, product, etc. is positive, negative, or neutral.

## What is Natural Language Processing (NLP)?

Natural Language Processing (NLP) is a field of computer science that focuses on the interaction between computers and humans. NLP is a way for computers to analyze, understand, and derive meaning from human language in a smart and useful way. By utilizing NLP, developers can organize and structure knowledge to perform tasks such as automatic summarization, translation, named entity recognition, relationship extraction, **sentiment analysis**, speech recognition, and topic segmentation.

## Technologies Used

* Python - version 3.11.5
* Pandas - version 2.1.2
* re - version 2.2.1
* NLTK - version 3.8.1
* sci-kit learn - version 1.3.2
* matplotlib - version 3.8.0