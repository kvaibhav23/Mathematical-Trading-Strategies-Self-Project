# Mathematical Trading Strategies

This project implements mathematical trading strategies by evaluating investment performance using various metrics such as Sharpe Ratio, Sortino Ratio, and Cumulative Returns. It also includes an analysis of the lead-lag relationship and correlation between selected indices using moving averages.

## Project Overview

The project consists of the following key components:

1. **Data Collection**: Fetching historical data for selected equities and international indices using `yfinance`.
2. **Performance Metrics**: Calculating Sharpe and Sortino Ratios to evaluate the risk-adjusted return of the investments.
3. **Cumulative Returns**: Analyzing the growth of investments over time by computing cumulative returns.
4. **Lead-Lag Analysis**: Investigating the lead-lag relationship and correlation between two indices using moving averages.

## Dependencies

The project requires the following Python libraries:
- `yfinance`
- `numpy`
- `pandas`
- `matplotlib`

Install the dependencies using:
```sh
pip install yfinance numpy pandas matplotlib
