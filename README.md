# European-Stocks-Selector-Optimizer

A Streamlit application for selecting and optimizing European stock portfolios using historical data.

## Features
- Extracts index components from Wikipedia (CAC 40, DAX, etc.)
- Filters stocks with at least 20 years of historical data and EUR currency
- Downloads adjusted prices from Yahoo Finance (to consider corporate actions)
- Optimizes portfolio using:
  - Minimum Variance
  - Maximum Return
  - Risk-Optimized Minimum Volatility
  - Custom Weights
  - Targeted Return
- Displays portfolio weights and sectors visually
- Displays portfolio performance over time (1M, 6M, 1Y, etc)

## Run locally
```bash
pip install -r requirements.txt
streamlit run app.py
