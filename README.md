# PSX-Portfolio-Optimization
Applied Modern Portfolio Theory and numerical optimization to construct and evaluate equity portfolios.

# Project Overview

This project applies Modern Portfolio Theory (MPT) to construct and evaluate optimal portfolios using selected equities listed on the Pakistan Stock Exchange (PSX).
Using approximately ten years of historical stock price data, the analysis examines the relationship between portfolio returns and risk and explores how different asset allocation strategies affect portfolio performance.

# Methodology

The project covers:

- Historical stock price retrieval using Yahoo Finance.
- Calculation of daily logarithmic returns.
- Annualized expected returns and covariance matrix estimation.
- Correlation analysis across selected equities.
- Construction of equal-weighted, minimum-variance and maximum-Sharpe portfolios.
- Efficient frontier estimation using numerical optimization (SLSQP).
- Portfolio backtesting and cumulative performance analysis.
- Drawdown analysis to assess historical downside performance.

# Portfolio Strategies

- Equal-Weight Portfolio
- Minimum Variance Portfolio
- Maximum Sharpe Ratio Portfolio

# Technologies Used

Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- yfinance

# Data

Historical stock price data is retrieved through Yahoo Finance for selected PSX-listed equities.

# Repository Contents

PSX_Portfolio_Optimization.ipynb – Complete Python implementation and analysis.

# Disclaimer

This project is for educational and research purposes only. Historical performance does not guarantee future returns. Portfolio estimates depend on the assumptions and historical data used in the analysis.
