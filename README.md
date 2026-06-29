# Quant Learning

This repository records my learning projects in Python for finance and quantitative trading.

## Project 01: Stock Analysis

In this project, I used Python to analyze stock price data.
## Project 02: Multi-Stock Comparison

### Overview

Compared the stock performance of AAPL, MSFT, NVDA, TSLA, and GOOGL using Python.

### What this project does

- Downloaded historical stock price data using yfinance
- Calculated daily returns
- Calculated total returns
- Calculated volatility
- Plotted normalized stock performance
- Compared return and risk across multiple stocks

### Key Findings

- NVDA had the highest total return during the selected period.
- TSLA had the highest volatility, meaning it had the largest daily price movements.
- MSFT had the lowest volatility among the selected stocks.
- Higher return often comes with higher risk.
### Project 03: Risk Metrics Analysis

### Overview

Analyzed risk and return metrics for AAPL, MSFT, NVDA, TSLA, and GOOGL.

### What this project does

- Downloaded historical stock price data using yfinance
- Calculated daily returns
- Calculated annualized return
- Calculated annualized volatility
- Calculated Sharpe ratio
- Calculated maximum drawdown
- Plotted cumulative returns
- Plotted drawdowns

### Key Findings

- Compared stocks using both return and risk metrics.
- Annual return shows average yearly performance.
- Annual volatility shows yearly risk level.
- Sharpe ratio helps compare risk-adjusted return.
- Maximum drawdown shows the worst decline from a previous peak.

### What I did

- Downloaded stock data using yfinance
- Compared AAPL, TSLA, and NVDA
- Calculated daily returns
- Calculated total return and volatility
- Plotted moving averages

### Tools

- Python
- yfinance
- pandas
- matplotlib
### What this project does
Downloads stock price data
Compares AAPL, TSLA, and NVDA
Calculates daily returns
Calculates total return and volatility
Plots moving averages
### How to run
Install dependencies:
pip install -r requirements.txt
Open the notebook or Python file.
Run the cells or script from top to bottom.
### Files
01_stock_analysis.ipynb
requirements.txt
### Next Steps
Add more tickers
Compare standardized performance
Build a simple moving average strategy
Add a basic backtest
