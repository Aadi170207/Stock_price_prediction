# Stock_price_prediction
Stock Price Prediction using XGBoost (Time Series Forecasting) A lightweight and stable machine learning project that predicts stock closing prices using historical data from Yahoo Finance. The project applies time series feature engineering with XGBoost and is designed to run smoothly on low-resource systems.

# 📈 Stock Price Prediction using XGBoost

This project implements (stock price time series forecasting), using [XGBoost], a powerful and efficient machine learning algorithm.  
Historical stock price data is collected from [Yahoo Finance], and lag-based features are used to predict future closing prices.

## 📌 Project Overview

Stock market prediction is a challenging task due to the volatile and non-linear nature of financial markets.  
Rather than attempting exact long-term predictions, this project focuses on short-term forecasting by learning patterns from past stock prices.
Time series data is transformed into a supervised learning problem using lag features, and an XGBoost regression model is trained to make predictions.

## 🎯 Objectives

- Collect historical stock price data  
- Perform time series feature engineering  
- Train an XGBoost regression model  
- Predict future stock closing prices  
- Evaluate model performance using RMSE  

## 🛠 Skills & Technologies Used

- Time Series Forecasting  
- Machine Learning  
- Feature Engineering  
- Python  
- XGBoost  
- Libraries:
  - `pandas`
  - `numpy`
  - `yfinance`
  - `scikit-learn`
  - `xgboost`

## 📂 Project Structure

├── stock_prediction.ipynb # Jupyter Notebook (data analysis & model)
├── README.md # Project documentation
