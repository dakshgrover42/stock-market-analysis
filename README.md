# Stock-Market-Analysis-using-Python

📊 Stock Market Analysis using Python
Welcome to this end-to-end Stock Market Analysis project built using Python and essential data science libraries. This notebook demonstrates how to retrieve, process, visualize, and analyze real-world stock market data using Modern Portfolio Theory (MPT) concepts.

We apply this analysis to four major Indian stocks: Reliance, TCS, Infosys, and HDFC Bank.

✅ Project Objectives
📥 Fetch historical stock data from Yahoo Finance

🔍 Clean and structure raw financial time series data

📈 Visualize price trends and moving averages

📊 Explore daily return distributions and inter-stock correlations

💡 Simulate portfolios to find optimal risk-adjusted allocations

🧠 Apply Sharpe Ratio to identify the best-performing portfolio

🍰 Present portfolio weights through clean visuals

🧱 Project Structure & Key Steps
1. Data Collection
Retrieved 1-year OHLCV data (Open, High, Low, Close, Volume) for selected stocks using the yfinance API.

Converted raw multi-level data into a tidy format.

2. Exploratory Data Analysis (EDA)
Visualized Adjusted Close prices over time with 50-day and 200-day Moving Averages.

Plotted daily trading volumes to examine market activity.

3. Return Calculations
Computed daily percentage returns per stock.

Visualized the distribution of returns using histograms and KDE (Kernel Density Estimation).

4. Correlation Analysis
Generated a correlation heatmap of daily returns to understand stock relationships and diversification potential.

!image[image alt](https://github.com/dakshgrover42/stock-market-analysis/blob/main/Screenshot%20(19).png?raw=true)

6. Portfolio Simulation
Used Monte Carlo simulation to generate 10,000 random portfolios with varying weights.

Calculated expected returns, volatility, and Sharpe Ratios for each.

Plotted the Efficient Frontier to visualize the trade-off between return and risk.

6. Optimal Portfolio Selection
Identified the portfolio with the maximum Sharpe Ratio.

Extracted and displayed its exact allocation across the four stocks.

7. Visualization of Final Allocation
Displayed the optimal allocation using a pie chart and summary table, highlighting the dominant stock.

🧾 Conclusion
This project serves as a comprehensive demonstration of how Python empowers financial analysis, enabling data-driven portfolio decisions with just a few libraries. The techniques shown are foundational for quantitative finance, algorithmic trading, or personal investment optimization.



