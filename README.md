# Project Proposal - Predicting Global Markets Based on Sentiment

## Team Members:
1) Justin John  
2) Stephan Bernard   
2) Farah Awad  
3) Christopher Larson   

## Project Outline: 
Using the Natural Language Processing features to feed into a machine learning model that will predict movement of stock prices & percent change in global markets. 

## Research Questions to Answer

- How do global markets fluctuate based on U.S news sentiment analysis of market indicies?
- Markets to predict daily percent change - SP500(USA), FTSE 100(UK), FCHI CAC 40(FR), GDAXI(GER), TOPIX(Japan)
- How are major global markets going to perform in the next 5 days?

## Data sources to be used
- New York Times: https://developer.nytimes.com/apis
- Google Finance: Global Indices Stock Prices


## Machine Learning Models & NLP Kits
 - IBM Watson NLP https://www.ibm.com/cloud/watson-natural-language-understanding
 - LSTM Model
 - Balanced Random Forest Classifier Model

## Task Breakdown
- Fetch 90 days worth of closing price data for global indicies using Quandl API
- Fetch 90 days worth of news data using Google News API or other
- NLP - sentiment analysis using IBM Watson to score current
- Machine Learning (create model, fit model, evaluate model and show predictions)- use any model that you see fit(one or more)
