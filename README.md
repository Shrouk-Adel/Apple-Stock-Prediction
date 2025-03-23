# Stock Market Analysis & Prediction

## Overview
This project analyzes and predicts stock prices for major technology companies (Apple, Amazon, Google, and Microsoft) using historical market data. The analysis includes visualization of price trends, calculation of moving averages, and daily returns. The centerpiece of the project is a Bidirectional LSTM neural network model that achieves an impressive 97% accuracy (R² score) in predicting Apple (AAPL) stock prices.

## Key Features
- **Historical Data Analysis**: Visualization of closing prices and trading volumes
- **Technical Indicators**: Implementation of moving averages (10, 20, and 50 days)
- **Price Prediction**: Advanced Bidirectional LSTM model for stock price forecasting

## Data Source
The project uses Yahoo Finance data accessed through the `yfinance` API to obtain real-time and historical stock information.

## Model Architecture
The prediction model utilizes a sophisticated Bidirectional LSTM neural network with:
- Two Bidirectional LSTM layers (128 and 64 units)
- Dropout regularization to prevent overfitting
- L2 regularization for improved generalization
- Early stopping to optimize training

## Results
The model achieved outstanding performance metrics:
- **R² Score: 97%** - Indicates the model explains 97% of the variance in stock prices
- **Low RMSE** - Demonstrates high prediction accuracy in absolute terms

## Visualizations
The project includes multiple visualizations:
- Closing price trends
- Trading volume analysis
- Moving averages comparison
- Daily returns distribution
- Actual vs. predicted stock prices

## Insights
- All four tech stocks (AAPL, GOOG, MSFT, AMZN) experienced a decline in 2022 followed by a rebound
- Apple and Microsoft showed stronger recovery patterns with prices climbing above key moving averages
- 10 and 20-day moving averages were found to be optimal for capturing meaningful trends while filtering noise

## Requirements
- Python 3.x
- Required libraries: 
  - Data manipulation: pandas, numpy
  - Visualization: matplotlib, seaborn
  - Finance data: yfinance, pandas-datareader
  - Machine learning: scikit-learn, tensorflow

 
