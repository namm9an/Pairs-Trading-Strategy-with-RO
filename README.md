# Pairs-Trading-Strategy-with-RO
Project Overview:
This project implements a pairs trading strategy with a focus on risk optimization using Brazilian stocks. Pairs trading is a market-neutral strategy involving the simultaneous purchase and sale of two correlated securities. The goal is to leverage statistical arbitrage opportunities while managing risk effectively.

Introduction: 
This project utilizes statistical arbitrage to identify pairs of Brazilian stocks for trading. By optimizing risk metrics, we aim to improve the performance and robustness of the trading strategy.

Data Collection: 
The notebook fetches historical data for Brazilian stocks using yfinance. Data is preprocessed and cleaned for analysis.

Pairs Identification:
We use statistical methods like cointegration and correlation to identify pairs of stocks. Pairs with the highest cointegration scores are selected for trading.

Trading Strategy:
The pairs trading strategy is implemented with defined entry and exit rules based on z-scores of the price spread. This ensures market neutrality and capitalizes on the mean-reverting behavior of the pairs.

Risk Optimization:
A risk optimization framework is developed to manage trading risks. This includes using metrics such as the Sharpe ratio, maximum drawdown, and other risk-adjusted performance measures.

Backtesting: 
The strategy's performance is evaluated using historical data. Key performance metrics like Sharpe ratio, maximum drawdown, and cumulative returns are analyzed to assess the strategy's effectiveness.

Visualization:
Stock prices, z-scores, trading signals, and portfolio performance are plotted for better insights into the strategy's behavior and effectiveness.

Getting Started
Prerequisites 
Python 3.6 or higher 
Jupyter Notebook or Google Colab
Libraries: pandas, numpy, matplotlib, statsmodels, scipy, sklearn, yfinance


