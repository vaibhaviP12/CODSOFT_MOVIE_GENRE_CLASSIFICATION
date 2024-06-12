# CODSOFT_MOVIE_GENRE_CLASSIFICATION
This repository contains a machine learning model that predicts the genre of a movie based on its plot summary. The model is implemented using techniques like TF-IDF vectorization and classifiers such as Naive Bayes and Logistic Regression. Additionally, a basic chatbot interface is provided where users can input a movie plot description and get the predicted genre.

## Introduction

The goal of this project is to create a machine learning model that can accurately predict the genre of a movie based on its plot summary. This is achieved through the following steps:
- Data preprocessing
- Feature extraction using TF-IDF
- Training models using Naive Bayes and Logistic Regression
- Evaluating the models
- Implementing a chatbot interface for user interaction
  
## Dataset

The dataset used in this project consists of movie titles, genres, and plot descriptions. The data is provided in two text files:
- `train_data.txt`: Contains the training data with movie titles, genres, and plot descriptions.
- `test_data.txt`: Contains the test data with movie titles and plot descriptions.

## Exploratory Data Analysis

The script includes visualizations for:
- Distribution of movie genres.
- Distribution of description length.

## Model Training

The script preprocesses the text data by:
- Converting text to lowercase.
- Removing punctuation.
- Removing stopwords.

Features are extracted using TF-IDF vectorization. Two models are trained:
- Naive Bayes
- Logistic Regression

## Evaluation

The models are evaluated using:
- Accuracy score
- Classification report

## Chatbot Interface

A simple chatbot interface is provided to input a movie plot description and receive genre predictions from both Naive Bayes and Logistic Regression models.


