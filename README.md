[README.md](https://github.com/user-attachments/files/29608392/README.md)
# Stock Portfolio Analyzer

## Project Overview

This project analyzes a stock portfolio using Python, Google Colab, and real market data from Yahoo Finance. The portfolio uses five example stocks: Apple, Microsoft, Nvidia, JPMorgan Chase, and Exxon Mobil. The starting investment is $10,000.

The notebook calculates portfolio returns, volatility, allocation, correlations, cumulative performance, Sharpe ratio, and best/worst performing stocks. It also includes charts and a final summary so the results are easy to understand.

## Business Use Case

This type of analysis can help investors and finance teams understand how a portfolio performed, where the risk is coming from, and which stocks had the biggest impact on overall performance.

## Tools Used

- Python
- Google Colab
- yfinance
- pandas
- numpy
- matplotlib
- plotly

## Main Features

- Downloads historical stock prices using yfinance
- Allows custom ticker and investment amount inputs
- Calculates daily returns and annualized returns
- Measures risk and volatility
- Shows portfolio allocation
- Builds a correlation heatmap
- Creates cumulative return charts
- Calculates the Sharpe ratio
- Identifies best and worst performing stocks
- Generates a dashboard-style portfolio summary
- Exports key results as CSV files

## Example Portfolio

| Ticker | Company |
|---|---|
| AAPL | Apple |
| MSFT | Microsoft |
| NVDA | Nvidia |
| JPM | JPMorgan Chase |
| XOM | Exxon Mobil |

Starting investment: **$10,000**

## How to Run

1. Open Google Colab.
2. Upload `Stock_Portfolio_Analyzer_Clean.ipynb`.
3. Run the notebook from top to bottom.
4. Change the tickers or starting investment if needed.
5. Review the tables, charts, and final portfolio summary.

## Key Metrics

The notebook focuses on practical portfolio metrics:

- **Return:** how much the investment gained or lost.
- **Volatility:** how much the stock prices moved up and down.
- **Correlation:** how closely the stocks moved together.
- **Sharpe Ratio:** how much return the portfolio earned compared with its risk.
- **Allocation:** how the investment is divided across stocks.

## Project Takeaway

This project shows how Python can be used for real financial analysis. It combines market data, portfolio calculations, risk measurement, data visualization, and business-style reporting in one notebook.
