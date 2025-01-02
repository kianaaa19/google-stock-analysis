# Google Stock Market Analysis and Prediction (GOOGL)

## Overview
This project is focused on analyzing the stock market data for Alphabet Inc. (GOOGL), using the `yfinance` library to retrieve historical pricing data. Key analyses include examining stock prices, calculating moving averages, daily returns, volatility, and ultimately, predicting future stock prices using linear regression.

## Project Understanding
The primary goal of this project is to understand the historical trends and behaviors of GOOGL’s stock price, explore different financial metrics, and apply predictive modeling techniques to forecast future stock movements. The insights gained from analysis and predictions can assist investors and analysts in making informed decisions regarding stock investments.

## Data Understanding
The dataset consists of historical market data retrieved via the `yfinance` package, which includes the following key features:
- **Date**: The date on which the stock price was noted.
- **Open**: The price at which the stock opened on that date.
- **High**: The highest price the stock reached during the trading session.
- **Low**: The lowest price the stock reached during the trading session.
- **Close**: The price at which the stock closed on that date.
- **Volume**: The number of shares traded during the session.
- **Dividends**: The dividend payout for the stock.
- **Stock Splits**: Any stock splitting events that occurred.

With a comprehensive view of the stock's trading history, investors can glean insights about performance over time.

## Data Processing
The data processing phase involves:
- **Downloading Historical Data**: Leveraging the `yfinance` library to fetch historical stock data for GOOGL, spanning a considerable period.
- **Data Cleaning**: Ensuring the data is clean and properly structured for analysis, including parsing the dates and setting them as the index for the DataFrame.
- **Feature Engineering**: Creating new variables such as moving averages, daily returns, and rolling volatility to enrich the analysis.

## Exploratory Data Analysis (EDA)
EDA is conducted to visually and quantitatively examine the performance characteristics of GOOGL stock. This step involves:
1. **Moving Averages**: Visualizing 50-day and 200-day moving averages to identify trends.
2. **Daily Returns**: Analyzing the daily return percentage to assess volatility and average returns.
3. **Volatility Metrics**: Calculating rolling volatility over specific windows to understand price fluctuations.
4. **Trading Volume Analysis**: Examining the trading volume over time to gauge market interest.
5. **Support and Resistance Levels**: Determining key price levels where the stock consistently bounces up or down.
6. **Correlation Analysis**: Comparing GOOGL’s stock performance with other class of shares (GOOG) to understand market dynamics.

## Modeling
The modeling phase focuses on predictive analytics to estimate future stock prices using linear regression. This method entails:
- **Feature Selection**: Using the numerical day count as an independent variable and the closing price as the dependent variable.
- **Training and Testing**: Dividing the dataset into training and testing sets to build and evaluate the model.

The linear regression model allows for exploration of relationships between stock price movements and time, providing a straightforward approach to price forecasting.

## Evaluation
The evaluation involves assessing the model's predictions against actual closing prices to determine its accuracy. The result of the correlation analysis also serves to underscore the relationship between GOOGL’s stock and other stocks in a more statistical context.

## Conclusion
The project successfully demonstrates the retrieval, processing, and analysis of historical stock data for GOOGL. Through the use of various financial metrics and predictive modeling techniques, insights into stock behavior and future price tendencies are established. This analytical framework lays the groundwork for more complex analyses and model improvements, potentially incorporating machine learning algorithms for enhanced predictive capabilities in future iterations. The findings and models can thus serve as valuable tools for investors and analysts looking to make data-driven decisions in the stock market.
