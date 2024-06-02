# BTC Trading Metrics Script

This repository contains a Python script / Jupyter Notebook for analyzing BTC trading metrics using historical data from Binance. The script performs various tasks including fetching historical data, calculating moving averages, computing the Relative Strength Index (RSI), and evaluating volatility. It also includes asset selection based on liquidity and volatility factors.

## Features

- **Fetch Historical Data**: Retrieve historical BTC/USDT data from Binance.
- **Calculate Moving Averages**: Compute 50-day and 200-day moving averages.
- **Plot BTC Price and Moving Averages**: Visualize BTC price along with moving averages.
- **Calculate RSI**: Compute the Relative Strength Index to evaluate overbought or oversold conditions.
- **Plot BTC Price and RSI**: Visualize BTC price and RSI over time.
- **Calculate Volatility**: Compute and plot annualized volatility of BTC.
- **Asset Selection**: Select assets based on liquidity and volatility factors.
- **Sharpe Ratio Calculation**: Compute the Sharpe Ratio to assess risk-adjusted returns.
- **Investment Strategies**: Provide insights into asset allocation, dollar-cost averaging, and risk management.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/jeroba/btc-trading-metrics.git
    ```
2. Navigate to the project directory:
    ```bash
    cd btc-trading-metrics
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Create a `.env` file in the same directory as the script and add your Binance API credentials:
    ```plaintext
    API_KEY=your_api_key
    API_SECRET=your_api_secret
    ```
2. Run the script: Run the cells of the notebook 

## Dependencies

- `python-binance`
- `pandas`
- `numpy`
- `matplotlib`
- `python-dotenv`
