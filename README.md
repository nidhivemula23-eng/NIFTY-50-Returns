# NIFTY 50 Returns Analysis - Impact of CPI Inflation & RBI Repo Rate

## Overview
Wanted to understand whether macroeconomic indicators like inflation and 
the RBI's policy rate actually move the stock market or whether the 
market had already priced them in before the data even came out.

This project uses OLS regression to test the relationship between CPI 
inflation, RBI repo rate, and NIFTY 50 monthly returns across a 10-year 
period.

## Data
- **Period:** January 2014 – November 2023
- **Observations:** 119 monthly data points
- **Variables:**
  - Dependent: NIFTY 50 monthly returns
  - Independent: CPI Inflation (%), RBI Repo Rate (%)

## Methodology
- Ordinary Least Squares (OLS) Regression
- Tested for multicollinearity, heteroscedasticity, and serial correlation
- Analysed coefficient significance and overall model fit

## Key Findings
- R² of 0.54% — macroeconomic variables explain very little of NIFTY 50's 
  monthly return variation
- Neither CPI nor repo rate showed statistically significant predictive power
- Conclusion: Consistent with the **Efficient Markets Hypothesis (EMH)** — 
  publicly available macro data is already reflected in market prices by the 
  time it is released

## Tools Used
- Microsoft Excel (data cleaning, regression analysis, visualisation)

## What I Learned
Markets are harder to predict than they look. The EMH isn't just a theory, 
this project gave me a firsthand look at why even clean, structured 
macroeconomic data fails to consistently explain equity returns.

## Author
Nidhi Vemula - Economics Graduate, Pillai University
Executive Programme in Business Analytics & AI, IIM Ranchi
