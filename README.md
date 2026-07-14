# Trader Performance vs Market Sentiment Analysis

## Project Overview

This project analyzes the relationship between Bitcoin market sentiment and Hyperliquid trader performance. The analysis was performed by combining the Bitcoin Fear & Greed Index with historical trading data to understand how market sentiment influences trader behavior and trading performance.

## Datasets Used

1. Bitcoin Market Sentiment (Fear & Greed Index)
2. Hyperliquid Historical Trader Data

## Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

- Loaded both datasets
- Checked missing values and duplicate records
- Converted timestamps into date format
- Merged both datasets using the date column
- Created key metrics such as Daily PnL, Win Rate, Trade Frequency, Position Size, and Long/Short Ratio
- Performed data analysis using charts and tables
- Identified key insights
- Suggested strategy recommendations

## Key Findings

- Traders earned higher average profits during Extreme Greed market conditions.
- Win rates were higher during positive market sentiment compared to Fear periods.
- Trading activity and position size changed across different market sentiment categories.

## Project Files

- Trader_Performance_vs_Market_Sentiment.ipynb
- README.md
- fear_greed_index.csv
- historical_data.csv