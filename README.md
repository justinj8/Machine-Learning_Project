# Project Proposal - Predicting Global Markets Based on Sentiment

## Team Members:
1) Justin John  
2) Stephan Bernard   
2) Farah Awad  
3) Christopher Larson   

## Project Outline: 
Using the Natural Language Processing features to feed into a machine learning model that will predict movement of stock prices in global markets. 

## Research Questions to Answer

- How do global markets fluctuate based on news sentiment analysis of market indicies?
- Markets to predict daily percent change - NDAQ(USA), FTSE 100(UK), FCHI CAC 40(FR), GDAXI(GER), SSE Composite (China)
- How are major global markets going to perform in the next 7 days with upcoming us presdential elecitons?

## Data souces to be used
- Google News https://newsapi.org/s/google-news-api
- Reuters https://www.reutersagency.com/en/platforms/api-feeds/
- Quandl Api for Indicies https://www.quandl.com/data/NASDAQOMX-NASDAQ-OMX-Global-Index-Data/documentation

## Machine Learning Models & NLP Kits
 - IBM Watson NLP https://www.ibm.com/cloud/watson-natural-language-understanding
 - Linear Regression Model 
 - Logistic Regression Model 
 - New machine learning library to be used: PyTorch or Theano https://blog.bitsrc.io/top-5-javascript-machine-learning-libraries-604e52acb548

## Task Breakdown
- Fetch 90 days worth of closing price data for global indicies using Quandl API
- Fetch 90 days worth of news data using Google News API or other
- NLP - sentiment analysis using IBM Watson to score current
- Machine Learning (create model, fit model, evaluate model and show predictions)- use any model that you see fit(one or more)
- Presentation slides 