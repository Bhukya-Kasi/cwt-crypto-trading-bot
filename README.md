# CWT Crypto Trading Bot

Crypto trading bot for CrowdWisdomTrading internship application.

## Features

- Fetches last 200 5-minute bars for Bitcoin and Ethereum using yfinance
- Predicts next 5-minute price movement (up/down)
- Risk management using Kelly Criterion formula
- Feedback loop to track prediction accuracy
- Supports multiple crypto assets

## How to Run

### On Google Colab (Recommended)

1. Open Google Colab
2. Upload `cwt_crypto_bot.ipynb`
3. Run all cells

### Locally

```bash
pip install yfinance pandas numpy
python crypto_trading_bot.py
