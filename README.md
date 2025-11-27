Machine Learning Project – Financial Resilience Analysis
ESILV – A4 / Machine Learning

--------------------------------------------------------
Objective of the project
This project investigates the following research question:

Do Middle Eastern investment portfolios demonstrate greater financial resilience compared to European portfolios when facing global market fluctuations?

To address this question, we analyze and compare:

- Tadawul All Share Index (TASI) — Middle Eastern market
- EURO STOXX 50 — European market
- VIX Index — global volatility indicator
- Brent Crude Oil — macroeconomic risk factor  

We build machine learning models, compute financial risk metrics, and analyze market sensitivity to evaluate which region is more resilient under stress.

--------------------------------------------------------
Methods and Analyses

1. Data Processing
- Time alignment of datasets  
- Handling missing values  
- Computing daily returns  
- Merging datasets for joint analysis  

2. Machine Learning Modeling
Models tested:
- Linear Regression  
- Ridge Regression  
- Random Forest  
- Support Vector Regression  
- Grid Search  
- Time-series cross-validation  
- Ensemble methods (Bagging, Voting, Stacking)

3. Financial Risk Metrics
To evaluate resilience:
- Rolling volatility  
- Distribution of returns  
- Maximum drawdown  
- Sharpe ratio  
- Value-at-Risk (VaR)  
- Expected Shortfall (ES)  
- Beta vs VIX  

4. Econometric Analysis
- OLS regression (returns vs VIX & Brent)  
- GARCH volatility models  
- Stress testing  
- Rolling correlations with VIX and Brent  

--------------------------------------------------------
Key Insights (Preliminary)

- TASI shows lower and smoother volatility than EURO STOXX 50.  
- TASI is less sensitive to VIX shocks.  
- Brent Oil has strong influence on TASI movements.  
- ML models struggle to predict returns accurately, which is common in finance.  
- Ensemble methods offer small improvements, but R² remains close to zero.

Preliminary conclusion:  
TASI appears more resilient overall, showing lower drawdowns, lower volatility spikes, and lower beta to VIX compared to the European index.

--------------------------------------------------------
Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Statsmodels  
- arch (optional for GARCH)

--------------------------------------------------------
Authors
- Erian Stanley Yogaraj  
- Ouiam Boussaid Benchaara  

ESILV – A4 students, Machine Learning Project.


