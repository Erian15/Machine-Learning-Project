Machine Learning Project – Financial Resilience Analysis

ESILV – A4 IF1/ Machine Learning

--------------------------------------------------------
This project explores whether the Middle Eastern stock market (Tadawul All Share Index – TASI) demonstrates stronger financial resilience compared to a major European benchmark (EURO STOXX 50).
Using a combination of data analysis, risk metrics, econometric models, and machine-learning techniques, we analyze how each market reacts to global shocks such as volatility spikes (VIX) and oil price movements (Brent).

The notebook includes the full pipeline, from raw data to modeling, with clear comments and step-by-step results.

--------------------------------------------------------
Methods and Analyses

1. Data Cleaning & Preparation
- Convert dates and sort chronologically
- Clean price formats
- Compute daily returns
- Align datasets on shared calendar dates 

2. Exploratory Data Analysis (EDA)
- Price evolution plots
- Distributions of daily returns
- 30-day rolling volatility
- Maximum drawdown analysis

3. Risk & Resilience Metrics
- Sharpe Ratio
- Value-at-Risk (VaR 95%)
- Expected Shortfall (ES 95%)
- Maximum Drawdown

4. Econometric Modeling
- OLS regressions: market returns explained by VIX & Brent
- Interpretation of sensitivity to global risk 

5. Machine Learning Models
- Several models are tested using Time Series Cross-Validation:
- Linear Regression
- Ridge Regression
- SVR (RBF kernel)
- Random Forest Regressor Volatility Modeling 

6. We estimate GARCH(1,1) models to measure conditional volatility and persistence.
This helps identify periods of volatility clustering and compare structural stability across markets.

Goal: evaluate how predictable short-term equity returns are.

--------------------------------------------------------
Key Insights (Preliminary)

- TASI appears structurally more resilient, with smoother volatility, weaker reactions to global market stress, and smaller drawdowns.
- EURO STOXX 50 shows stronger sensitivity to VIX and Brent, with more pronounced volatility clustering.
- ML models perform weakly, confirming that daily returns are inherently noisy and difficult to predict.
- GARCH results show high volatility persistence in both markets, but TASI remains slightly more stable.
- 
--------------------------------------------------------
Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Statsmodels
- ARCH library
- Scikit-Learn

--------------------------------------------------------
Authors
- Erian Stanley Yogaraj  
- Ouiam Boussaid Benchaara  

ESILV – A4 IF1 students, Machine Learning Project.


