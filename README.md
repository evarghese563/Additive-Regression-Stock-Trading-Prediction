# Additive Regression Stock Trading Prediction
This is a webapp that was created to show the Additive Regression Model to predict the stock market using Streamlit, Fbprophet, and Yfinance. The Webapp uses Streamlit to project the data, fbprophet to implement the Additive Regression Model and yfinance as the api to retrieve stock market data. The Model is capable of predicting 4 years into the future using the model. Due to data constraints the model takes a while to load the data so currently the application is limited to Apple (AAPL), Google (GOOG), Microsoft (MSFT), Gamestop (GME), and Krispy Kreme Donuts (DNUT). However if you wish to add more stocks or take out the stocks in it you can edit the line:

`stocks = ("AAPL", "GOOG", "MSFT", "GME", "DNUT")`

By adding any stock ticker or by removing a stock ticker.

## Overview
![alt gif](https://github.com/evarghese563/Images/blob/main/ToGit/Overview.gif)
