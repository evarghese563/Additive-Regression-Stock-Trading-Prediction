# Additive Regression Stock Trading Prediction
This is a webapp that was created to show the Additive Regression Model to predict the stock market using Streamlit, Fbprophet, and Yfinance. The Webapp uses Streamlit to project the data, fbprophet to implement the Additive Regression Model and yfinance as the api to retrieve stock market data. The dataset is taken from 2015 to present day and the app is capable of predicting 4 years into the future using Additive Regression. 

To run this app 
`streamlit run main.py`


## Overview
![alt gif](https://github.com/evarghese563/Images/blob/main/ToGit/Overview.gif)

An overview of the components in the Web App

## Changing Dataset
![alt gif](https://github.com/evarghese563/Images/blob/main/ToGit/Changing%20Data.gif)

To change the dataset the please press the Selction box to switch between the different stocks

Due to the data load time for new stocks the model takes a while to load the data so currently the application is limited to Apple (AAPL), Google (GOOG), Microsoft (MSFT), Gamestop (GME), and Krispy Kreme Donuts (DNUT). However if you wish to add more stocks or take out the stocks in it you can edit the line:

`stocks = ("AAPL", "GOOG", "MSFT", "GME", "DNUT")`

By adding any stock ticker or by removing a stock ticker.


## Time Series Data
![alt gif](https://github.com/evarghese563/Images/blob/main/ToGit/Time%20Series.gif)

For the Time Series the dataset is switched over to the Krispy Kreme Donut dataset to show the variation in the stock market closing and opening prices. Since Kirspy Kreme is an IPO during the time the app was created the variations of the data are clearly shown but are limited to only a few months.

## Additive Regression Year 1
![alt gif](https://github.com/evarghese563/Images/blob/main/ToGit/ML%201.gif)

FBprohet uses additive time series forecasting model, and the implementation supports trends, seasonality, and holidays. Here it is used to predict Google Stock 1 year into the future.

## Additive Regression Year 3
![alt gif](https://github.com/evarghese563/Images/blob/main/ToGit/ML%202.gif)

Here the model is used to predict 3 years into the future. To change the years of prediction just slide the slider right underneath the selection box.

