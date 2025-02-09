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

##  Portfolio analysis in Excel and VBA

### 1. Investment Comparison  
Users can enter investment data and calculate **NPV (Net Present Value) and IRR (Internal Rate of Return)** automatically.  

The **"Comparison of Investments"** sheet includes macros that:  
- Allow data entry for multiple investments.  
- Automate **NPV and IRR calculations**.  
- Rank investment projects based on these metrics.  
- Generate a **clustered column chart** comparing NPV and IRR.  
- Include a **dynamic slider** next to the Discount Rate label that updates calculations in real-time.  

---

### 2. Portfolio Construction  
The workbook includes a structured **portfolio analysis**, supporting:  
- **Equally Weighted Portfolio**: Simple allocation strategy.  
- **Build Your Own Portfolio**: User-defined allocation.  
- **Minimum Variance Portfolio**: Optimization to minimize risk.  
- **Efficient Frontier**: Graphically represents **optimal portfolios** balancing risk and return.  
- **Stock Data Sheet**: Contains historical stock prices for calculations.  
- **Benchmark Customization**: Users can select a benchmark index for comparison (e.g., **IWM - Russell 2000 ETF**).  

---

## How to use it?

### **Requirements**  
- **Excel with macro support enabled**.

### **Investment Comparison**  
1. Open the **Comparison of Investments** sheet.  
2. Use the **Enter Data of Investments** macro to input investment projects.  
3. Adjust the **discount rate slider** to see real-time NPV changes.  
4. View the **results in an automatically updated clustered column chart**.  

### **Portfolio Construction**  
1. Navigate to the **respective portfolio sheets**.  
2. Modify **weights** manually or allow **VBA macros** to optimize allocations.  
3. View the **Efficient Frontier** for optimal portfolio selection. 
