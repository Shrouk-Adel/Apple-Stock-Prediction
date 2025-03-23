# Stock Market Analysis & Prediction

## Overview
This project analyzes and predicts stock market data for major technology companies (Apple, Amazon, Google, and Microsoft). Using historical stock data from Yahoo Finance, the project explores price trends, calculates moving averages, analyzes daily returns, and implements a Long Short-Term Memory (LSTM) neural network to predict future stock prices.

## Key Features
- Historical stock data visualization for tech giants
- Moving average calculations (10, 20, and 50 days)
- Daily return analysis and distribution
- Stock price prediction using LSTM neural networks
- Comprehensive performance visualization

## Questions Answered
1. What was the change in price of the stock over time?
2. What was the daily return of the stock on average?
3. What was the moving average of the various stocks?
4. How can we predict future stock behavior? (Applied to Apple stock)

## Technologies Used
- **Python**: Core programming language
- **Libraries**:
  - pandas & numpy: Data manipulation
  - matplotlib & seaborn: Data visualization
  - yfinance: Stock data acquisition from Yahoo Finance
  - scikit-learn: Data preprocessing
  - Keras/TensorFlow: LSTM model implementation

## Installation & Setup
```bash
# Install required packages
pip install numpy pandas matplotlib seaborn yfinance pandas-datareader scikit-learn keras tensorflow
```

## Usage
1. Clone the repository
2. Run the Jupyter notebook
3. Adjust the date ranges and stock tickers as needed

## Project Structure
- Data acquisition from Yahoo Finance
- Exploratory data analysis
- Visualization of closing prices and sales volumes
- Moving average calculations
- Daily return analysis
- LSTM model implementation for price prediction
- Model evaluation using RMSE
- Visualization of predictions against actual values

## Results
The LSTM model provides predictions for Apple stock prices with performance metrics including RMSE. Visualizations show the model's predictions against actual values.
