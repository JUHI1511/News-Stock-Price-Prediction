# News-Stock-Price-Prediction
# Aim
The principle focus of our project is to perform data cleaning and data analysis and train a
machine learning model using the most popular Machine Learning algorithm –Random Forest
in order to analyse the News data and predict the stock trend movements.
# Abstract
The prediction of stock prices in the market has always been an important task. However, due to the
market volatility, it is difficult to make the correct prediction solely based on historical stock data.
Therefore, in this project, with the analysis of daily news’ impact on stock markets, we identify some
key features that could be useful in stock price prediction and propose a machine learning model to
capture the dynamics of stock price trend with rich news textual information.
# Introduction
Stock price is closely associated with daily news. Positive news such as new acquisition opportunities,
strong earnings reports and good management governance can increase the price of certain stocks.
Negative news such as ineffective monetary policy, political uncertainty and natural disaster may
negatively affect the whole stock market. Various news may lead to different reactions on stock market.
Thus, when new information comes into public, it is important for investors to quickly identify its
impact and make correct corresponding predictions on stock price. This project, aims to evaluate the
stock trend movement and train Machine Learning model that will predict the value of the trend when
the respective prospective data is entered concerning the same.
# Overview
* Data Segmentation and Data Cleaning
* Exploratory Data Analysis using python’s data visualization libraries
* Training the model based on the historical data available
# DATASET:
The dataset we are working on is a combination of Reddit news and the Dow Jones Industrial Average
(DJIA) stock price from 2008 to 2016. The news dataset contains the top 25 news on Reddit of each day
from 2008 to 2016. The DJIA contains the core stock market information for each trading day such as
Open, Close, and Volume. The label of the dataset represents whether the stock price is increase (labeled
as 1) or decrease (labeled as 0) on that day. The total number of days in the dataset is 1989. During our
preliminary experiments, we split the dataset into train, validation and test. The train dataset contains
1526 days, around 76% of the total dataset. The validation and test datasets contain 85 days and 378
days respectively
# DATA SEGMENTATION AND DATA CLEANING:
* In this project, we have prepared a processed dataset by collecting the clear-cut data
available in online.
* Using pandas data frame, we have loaded the data
* By using regex expressions we cleaned the dataset by removing punctuations, spaces etc.
* By using the fillna we have filled all the cells with median values.
* Next we have tokenized the text data and for each token we applied lemmatization and converted the
 text into lower cased.
* Next we removed all stop words present in text data
# PROJECT DEPLOYMENT LINKS:
https://stock-market-analyzer.herokuapp.com/
# References:-
Deployment Resources
For Flask :
https://www.youtube.com/playlist?list=PLJ39kWiJXSiyAFG2W3CUPWaLhvR5CQmTd
For Streamlit and Heroku :
https://www.youtube.com/playlist?list=PLtqF5YXg7GLm
CvTswG32NqQypOuYkPRUE
https://www.youtube.com/playlist?list=PLqYFiz7NM_SN
2ZbhnbfwG4kTZ6oCh0aOM
