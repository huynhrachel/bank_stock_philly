
# 🏦 Bank Stock Analysis (JPM, BAC, PNC)

This project looks at stock data for three major U.S. banks — JPMorgan Chase (JPM), Bank of America (BAC), and PNC Financial (PNC). I used Python and Google Colab to download the data, clean it, explore trends, and create some visualizations. The goal is mainly to practice data analysis and see how these banks move over time.

---

## Banks Included

* JPM (JPMorgan Chase)
* BAC (Bank of America)
* PNC (PNC Financial)

I chose these because they're large, well-known banks and have very available and consistent market data.

---

## What the Notebook Does

1. Downloads historical stock prices using yfinance
2. Combines the three banks into one DataFrame
3. Cleans the column names to make the data easier to work with
4. Calculates daily returns for each bank
5. Creates basic visualizations:

   * Line charts of closing prices
   * Distribution plot of daily returns
   * Pairplot comparing the banks
6. Builds a correlation matrix and visualizes it with a heatmap + clustermap
7. Uses Plotly + Cufflinks to make interactive charts
8. Adds simple technical analysis:

   * 30-day moving average
   * Bollinger Bands

The whole notebook is meant to be simple, readable, and easy to follow.

---

## Tools & Libraries

* Python
* Google Colab
* pandas
* numpy
* yfinance
* matplotlib
* seaborn
* plotly / cufflinks

---

## How to Run

Option 1 — Open in Google Colab
Just click the “Open in Colab” link in the repo (it appears automatically because the notebook was uploaded from Colab).

Option 2 — Run locally

1. Install the libraries:
   pip install pandas numpy yfinance matplotlib seaborn plotly cufflinks

2. Open the notebook with Jupyter Notebook or VSCode.

---

## Project Structure

bank_stock_philly/
├── bank_stock.ipynb
├── bank_stock.py
└── README.md

---

## Quick Takeaways

* JPM and PNC move more steadily, with trends that follow broader market conditions.
* BAC tends to have slightly wider swings in daily returns.
* All three banks are positively correlated, but not identical in behavior.
* Technical indicators like moving averages and Bollinger Bands help smooth out noise and show general direction.

---

## Possible Future Add-Ons

* Compare these banks to a financial index (like S&P 500 or XLF)
* Add more banks, including regional ones
* Include RSI, MACD, or other indicators
* Build a small dashboard using Plotly or Streamlit


