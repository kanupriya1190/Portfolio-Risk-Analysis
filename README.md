# Portfolio Risk Analysis

## Project Overview

This project focuses on portfolio risk analysis and optimization using data science techniques. The main objective is to model and optimize a diversified portfolio using Monte Carlo simulations and CAPM (Capital Asset Pricing Model) analysis. Through this analysis, the project provides insights into the portfolio's risk-adjusted returns and sensitivity to market fluctuations, with a particular focus on achieving desired alpha and beta values with respect to major indices like the Nasdaq and the S&P 500.

## Key Objectives

- **Portfolio Optimization**: Develop and optimize a portfolio that balances risk and return, aiming for improved alpha and beta values.
- **Risk Analysis**: Understand and quantify the portfolio's exposure to market volatility and sensitivity using CAPM.
- **Simulation-Based Approach**: Leverage Monte Carlo simulations to forecast a range of potential outcomes and assess portfolio stability under varying conditions.

## Methodology

1. **Data Collection**: Gathered historical price data for selected assets in the portfolio from financial databases.
2. **Monte Carlo Simulations**:
   - Simulated thousands of potential future portfolio paths to understand the impact of volatility and return distributions on portfolio performance.
   - Analyzed the range of outcomes to identify optimal asset allocation and reduce downside risk.
3. **CAPM Analysis**:
   - Calculated the portfolio’s alpha and beta values relative to the Nasdaq and S&P 500 indices.
   - Analyzed beta values to understand market sensitivity, and alpha to measure excess returns beyond market expectations.
4. **Optimization and Tuning**:
   - Adjusted portfolio weights to maximize risk-adjusted returns.
   - Focused on balancing alpha and beta to achieve a target profile aligned with investment goals.

## Results

- **Alpha and Beta**: The optimized portfolio achieved an alpha of 0.0013 and beta of -0.002 relative to the Nasdaq, and an alpha of 0.0013 and beta of -0.005 with the S&P 500, highlighting its potential to deliver market-neutral returns with reduced risk.
- **Risk-Adjusted Performance**: Through Monte Carlo simulations, the portfolio demonstrated resilience to market volatility, with a favorable risk-return profile.
- **Market Sensitivity**: Low beta values indicate a portfolio less sensitive to overall market movements, offering a stable option for risk-averse investors.

## Skills and Tools Used

- **Programming Language**: Python
- **Libraries**: NumPy, Pandas, Matplotlib, Scikit-Learn, Statsmodels
- **Techniques**: Monte Carlo Simulations, CAPM Analysis, Portfolio Optimization
- **Data Sources**: Financial databases for historical price data (e.g., Yahoo Finance, Alpaca API)

## Conclusion

The portfolio risk analysis and optimization project successfully demonstrates how Monte Carlo simulations and CAPM can be applied to build a risk-adjusted investment portfolio. The results provide a foundation for understanding portfolio dynamics under different market conditions, helping investors make informed decisions based on alpha, beta, and overall risk exposure.

## Future Work

- **Extended Analysis**: Explore other financial models (e.g., Fama-French Three-Factor Model) for deeper insights.
- **Machine Learning Approaches**: Implement machine learning techniques for predictive modeling and dynamic asset allocation.
- **Real-Time Data Integration**: Integrate real-time data for continuous portfolio rebalancing and performance monitoring.
