#  Quantitative Portoflio Management projects

##  Black-Litterman Model
A tool built with Python and PyPortfolioOpt designed to optimize an investment portfolio using the Black-Litterman model to select assets, define market views and obtain an optimal allocation.

### Features
- Extraction of stock prices using Yahoo Finance (`yfinance`).
- Implementation of the **Black-Litterman model** to optimize portfolio allocation.
- Calculation of covariance matrices and estimation of expected returns.
- Portfolio optimization using **Efficient Frontier** (Max Sharpe Ratio).
- Generation of various plots to visualize:
  - Distribution of returns (prior & posterior).
  - Asset weights in a pie chart.
  - Covariance matrix of the selected assets.
  - Market trends and Black-Litterman posterior returns.

###  Code and libraries used
- **yfinance**: To fetch historical stock prices for selected assets and the market index.
- **pandas**: For data manipulation and handling of financial data.
- **numpy**: For mathematical operations and matrix manipulation.
- **matplotlib & seaborn**: For visualizing asset weights, expected returns, and covariance.
- **PyPortfolioOpt**:
  - `EfficientFrontier`: Portfolio optimization.
  - `BlackLittermanModel`: Black-Litterman implementation.
  - `risk_models`: Calculation of covariance matrices.
  - `plot_weights` and `plot_covariance`: For visualizing asset allocations and correlations.
