# AI Stock Market Prediction Bot

This project is a machine learning-based trading bot that analyzes historical stock data to generate long/short signals. It uses Python and financial technical indicators to build a predictive model and simulate a trading strategy.

## Features

- Fetches historical stock data using [Yahoo Finance](https://www.yfinance.info/)
- Calculates technical indicators (Moving Averages, Volatility, RSI, MACD, etc.)
- Trains a Random Forest classifier to predict stock direction
- Visualizes model performance (confusion matrix, returns)
- Simulates strategy returns based on prediction signals
- Outputs today's prediction (LONG / SHORT)

## Example Output


Bot decision: LONG (Price is expected to go up)


## Technologies Used

- Python (pandas, scikit-learn, matplotlib, seaborn)
- yFinance API
- RandomForestClassifier
- Time Series Analysis
- Strategy Backtesting

## Future Improvements

- Add live trading integration via Alpaca API
- Extend indicators and test with different ML algorithms
- Switch to LSTM model for sequence-based predictions
- Deploy via Streamlit as an interactive web app
- Send trading signals via Telegram or Discord bots

## Installation

1. Run the bot:
bash
python ai_trading_bot_code


## Disclaimer

This project is for *educational purposes only. It is **not financial advice*. Use it responsibly and test thoroughly before applying in real markets.

---

## License

MIT License – feel free to use, modify, and share!
"""

