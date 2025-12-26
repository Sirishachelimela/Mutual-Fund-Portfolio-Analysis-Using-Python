**Mutual Fund Portfolio Analysis Using Python**
Project Overview
_____________________________________________________________________________________________________________________________________________________________________________
This project focuses on building and evaluating a data-driven mutual fund portfolio using historical stock market data. The objective is to analyze returns and risk, construct a diversified portfolio, and assess its performance using industry-standard financial metrics. The analysis demonstrates how data analytics techniques can support informed investment decision-making.

Problem Statement
_____________________________________________________________________________________________________________________________________________________________________________
Investors aim to achieve optimal returns while managing risk. This project answers the following questions:

How can historical data be used to construct a diversified mutual fund portfolio?

How do risk and return vary across stocks?

How can portfolio allocation reduce volatility while maintaining growth?

How can performance be evaluated using risk-adjusted metrics?

Data Source
_____________________________________________________________________________________________________________________________________________________________________________
Source: Yahoo Finance

Market: Indian Equity Market (Nifty 50 stocks)

Time Period: Last 2 years

Price Type: Adjusted Closing Prices

Adjusted prices are used to reflect true investor returns after accounting for dividends and stock splits.

Tools and Technologies
_____________________________________________________________________________________________________________________________________________________________________________
Python

Pandas

NumPy

yfinance

Plotly

Methodology
_____________________________________________________________________________________________________________________________________________________________________________
1. Data Collection
Historical price data for selected Nifty 50 companies is downloaded using the Yahoo Finance API. The selected stocks form the investment universe for the analysis.

2. Data Preparation
Extracted adjusted closing prices

Converted prices into daily percentage returns

Removed missing values to ensure clean analysis

3. Feature Engineering
The following key metrics were calculated:

Return on Investment (ROI): Measures total growth over the analysis period

Volatility (Risk): Measured using the standard deviation of daily returns

Annualized Return: Expected yearly return based on historical data

Annualized Risk: Yearly volatility of returns

Sharpe Ratio: Measures risk-adjusted performance

4. Stock Selection
Stocks were selected using a rule-based approach:

Stocks with above-median returns or

Stocks with below-median risk

This ensures a balance between high-performing and stable stocks.

5. Portfolio Construction
An inverse-risk weighting strategy was applied:

Stocks with lower volatility received higher allocation

This approach emphasizes risk management and diversification

6. Portfolio Performance Evaluation
Portfolio returns were calculated using weighted daily returns

Cumulative growth was analyzed to understand compounding effects

Annualized metrics and Sharpe Ratio were used to evaluate performance quality

Visualization
_____________________________________________________________________________________________________________________________________________________________________________
An interactive line chart was created to show the growth of ₹1 invested in the portfolio over time. This visualization helps stakeholders easily understand long-term performance trends and portfolio stability.

Key Insights
_____________________________________________________________________________________________________________________________________________________________________________
Diversification reduces volatility compared to individual stock performance

Risk-based allocation leads to smoother portfolio growth

Evaluating returns without considering risk can be misleading

Sharpe Ratio provides a more realistic measure of portfolio performance

Business Value
_____________________________________________________________________________________________________________________________________________________________________________
This analysis can be used by:

Investors to understand risk-return trade-offs

Analysts to evaluate portfolio strategies

Financial teams to simulate and compare investment approaches

The project demonstrates how data-driven methods can support smarter investment decisions.

Conclusion
_____________________________________________________________________________________________________________________________________________________________________________
This project showcases the complete data analytics workflow:

Real-world data collection

Data transformation and feature engineering

Analytical modeling and portfolio construction

Performance evaluation and data storytelling

It highlights the ability to translate raw financial data into actionable insights using Python.
