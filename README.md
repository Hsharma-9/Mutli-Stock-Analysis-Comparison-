# Multi-Stock Comparison Analysis

Welcome to the Multi-Stock Comparison Analysis! This Python script helps you dive into the stock performance of three major automotive companies: Tesla (TSLA), Ford (F), and General Motors (GM). Here's a breakdown of what this script does and how to use it:

## Data Retrieval:

First, it grabs historical stock data from Yahoo Finance using the `yfinance` library (Note: Yahoo Finance API has been deprecated; the updated API is `yfinance` and must be imported as such).

It then saves this data into CSV files for easy access in the future.

## Visual Exploration:

The script creates visualizations to help you understand how these companies' stocks have performed over time.

You'll see line plots comparing their opening prices and trading volumes, helping you spot trends.

Rolling averages are used to smooth out the noise and show longer-term trends in stock prices.

Candlestick charts give you a detailed view of price movements over specific periods.

Histograms and kernel density plots help you gauge the volatility of daily returns for each company.

Boxplots offer a comparative view of how returns are distributed across the three companies.

## Cumulative Return Analysis:

Lastly, the script calculates and plots the cumulative return of each stock. This helps you understand how a $1 investment in each company would have grown over time.

## How to Use:

1. **Setup**: Make sure you have Python installed along with the necessary libraries: pandas, matplotlib, numpy, yfinance, and mplfinance.

2. **Running the Script**: Execute the Python script in an environment like Jupyter Notebook or any Python IDE.

3. **Customization**: Feel free to tweak the start and end dates for data retrieval to suit your analysis needs.

4. **Exploration**: Dive into the generated visualizations and analysis to gain insights into how Tesla, Ford, and GM have performed in the stock market.

## Requirements:

- Python 3.x
- pandas
- matplotlib
- numpy
- yfinance
- mplfinance

## Notes:

- The Yahoo Finance API has been deprecated; be sure to import the updated API using the updated library name `yfinance`.
- The `candlestick_ohlc` graph has been deprecated, so make sure to have `mplfinance` downloaded and use the import command from the original library to import it to your current version.




