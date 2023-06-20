# PrescriptiveAnalytics_StockPricePrediction

This repository contains the implementation of the thesis titled "Stock Price Prediction using Twitter Sentiment Analysis An Input-Process-Output Model Approach". The implementation is organized into multiple Jupyter notebooks, each focusing on a specific aspect of the thesis.

## Table of Contents

- [Instroduction](#introduction)
- [Notebook Descriptions](#notebook-descriptions)
- [Usage](#usage)
- [Contact](#contact)


## Introduction
This implementation is a project carried out as part of the Prescriptive Analytics class at the University of West Florida, under the guidance of Dr. Burch. The aim of this project is to demonstrate the application of Twitter sentiment analysis as a powerful tool for predicting stock prices. By leveraging natural language processing techniques and machine learning algorithms, this project explores the relationship between public sentiment on Twitter and stock market trends.

The implementation showcases a step-by-step process of collecting historical stock market data and associated Twitter data from different time periods. The tweets are associated with the corresponding stock chart to examine the correlation between Twitter sentiment and stock price movements. By analyzing the sentiment expressed in the tweets and comparing it with the historical stock data, this project aims to evaluate the effectiveness of using Twitter sentiment analysis as a tool for predicting stock prices.

## Notebook Descriptions

1. **Sentiment140.ipynb:** This notebook performs sentiment analysis using the Sentiment140 dataset and a Linear Support Vector Classifier (LinearSVC). It includes steps for data preparation, training the algorithm, and testing the model using confusion matrix visualization.

2. **SentimentAnalysis.ipynb:** This notebook extends the sentiment analysis to analyze the sentiment of specific text and a set of tweets. It uses the trained LinearSVC model from the Sentiment140 dataset to predict sentiment labels for the provided text and tweets.

3. **StockPrices.ipynb:** This notebook focuses on retrieving historical stock price data from Yahoo Finance for a specific company (current version: BASF) using the yfinance library. It prepares the data and visualizes weekly stock price charts.

4. **Tweets.ipynb:** This notebook demonstrates how to authenticate with the Twitter API using Tweepy and perform tasks such as user lookup and retrieving user information.

## Usage

### Sentiment Analysis:
Open the "Sentiment140.ipynb" Jupyter Notebook.
Run the notebook cells one by one to execute the sentiment analysis tasks.
The notebook will train a machine learning model using the Sentiment140 dataset and perform sentiment analysis on provided text and tweets.
Modify the text or tweets in the notebook to analyze different sentiments.
The notebook will display the predicted sentiment (positive or negative) for the input text and tweets.

### Stock Price Prediction:
+ Open the "StockPrices.ipynb" Jupyter Notebook.
+ Modify the comp variable with the desired company's ticker symbol (e.g., 'AAPL' for Apple Inc.) obtained from Yahoo Finance.
+ Run the notebook cells one by one to execute the stock price prediction tasks.
+ The notebook will retrieve historical stock price data for the specified company and generate charts.

### Twitter Data Analysis:
+ Open the "Tweets.ipynb" Jupyter Notebook.
+ Modify the username variable with the desired Twitter username.
+ Run the notebook cells one by one to execute the Twitter data analysis tasks.
+ The notebook will retrieve information about a specific Twitter user or a group of users.
+ The notebook will display the user's details, such as name, description, follower count, and tweet count.
+ Modify the user_fields parameter to specify additional user information to retrieve.
+ The notebook will convert the data into a Pandas DataFrame for easy analysis and manipulation.

##### Ensure that you have the necessary dependencies installed and the required datasets or APIs are accessible for the program to run smoothly.

## Contact 
For any inquiries or feedback, please contact is52@students.uwf.edu.
