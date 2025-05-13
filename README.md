# FedReserve-impact-on-Firm-level-decision

This repository, with main file 'Analysis.ipynb', contains Python scripts and visualizations analyzing the relationship between the **Federal Reserve's interest rate policy** and key economic and financial indicators, including:

- Firm-level R&D and operating expenses (e.g., Apple)
- Stock prices
- Revenue trends

The analysis uses **publicly available economic data** from the [Federal Reserve Economic Data (FRED)](https://fred.stlouisfed.org/) and financial information from [Yahoo Finance](https://finance.yahoo.com/), accessed programmatically using `pandas_datareader` and `yfinance`.

---

## 📊 Data Sources

- **FRED (Federal Reserve Economic Data)**  
  Accessed via `pandas_datareader`.  
  - `FEDFUNDS`: Effective Federal Funds Rate  
  - `UNRATE`: U.S. Unemployment Rate

- **Yahoo Finance**  
  Accessed via `yfinance` Python API.  
  - Daily/quarterly stock and financial data for firms like Apple (AAPL)

---

## 🔧 Requirements

Make sure to install the following Python packages:

```bash
pip install yfinance pandas pandas_datareader matplotlib statsmodels
