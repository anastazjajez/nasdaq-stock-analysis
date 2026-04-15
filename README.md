# NASDAQ Stock Analysis

## Project Overview
This project analyzes historical stock prices of five NASDAQ companies: Palantir (PLTR), Shopify (SHOP), Moderna (MRNA), Uber (UBER), and Airbnb (ABNB).

The goal was to collect stock price data, perform descriptive analysis, visualize trends, and evaluate dataset quality using key performance indicators (KPIs).

## Data Source
The data was collected using the `yfinance` Python library, which retrieves historical stock price data from Yahoo Finance.

Type of data used:
- Historical daily stock prices
- Time series format
- Closing price (`Close`) column

## Companies Analyzed
- Palantir (PLTR)
- Shopify (SHOP)
- Moderna (MRNA)
- Uber (UBER)
- Airbnb (ABNB)

## KPI Evaluation
The following KPIs were evaluated for each dataset:

- **Completeness** - no missing values were found
- **Latency** - historical daily prices were sufficient for time series analysis
- **Accuracy** - prices were within realistic financial ranges
- **Consistency** - no duplicate rows and correct data types were observed

## Final Takeaway
All datasets were complete, consistent, and accurate, with no missing values or duplicate records. The data sourced from Yahoo Finance provided reliable historical daily prices, making it suitable for time series analysis and cross-company comparison.

The analysis revealed differences in stock behavior across companies. Moderna (MRNA) showed the highest volatility, while Palantir (PLTR) and Shopify (SHOP) demonstrated stronger growth dynamics. Uber (UBER) and Airbnb (ABNB) showed moderate fluctuations, reflecting their positions in competitive platform-based markets.

Overall, this project shows how different industries and business models influence stock price behavior, which is important for understanding market dynamics and making informed investment decisions.
