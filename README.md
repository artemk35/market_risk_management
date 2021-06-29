# market_risk_management

The repository contains python code with tools used in market risk management. The tools can broadly be divided into two categories:
1) Tools to measure risk: 
* VaR and ES file contains code to derive such measures as:
  - Rolling volatility;
  - Historical VaR and Expected Shortfall
  - Analytical VaR and Expected Shortfall
  - Monte Carlo simulated VaR and Expected Shortfall
  - Parametric VaR (the same code can be found in Parametric VaR estimation and forecasting).
* Parametric VaR estimation and forecasting file also performs backtesting on the model, the backtest is presented visually, there is no formal test to evaluate the model's performance to forecast VaR. - this might be added later. 
2) Tools to measure the dependence structure of several variables among each other. 
* Risk Dependence Structure code contains the following functionality:
  - Rolling correlation between assets, the function is capable to calculate and plot pairwise rolling correlation, but it needs some modifications. 
  - Exceedance correlation function allows calculating correlations at different states of the market. The function has been tested (vs the original MatLab code from Andrew Patton) and provides the correct output. However, it still lacks input checks and documentation. 
  - Copula  
* Exceedance Correlation, The file contains code to calculate exceedance correlations and plot pairwise exceedance correlations for various assets.  



# Useful libraries/packages for risk management in python:

pyfolio - Portfolio and risk analytics in Python.

empyrical - Common financial risk and performance metrics.
fecon235 - Computational tools for financial economics include: Gaussian Mixture model of leptokurtotic risk, adaptive Boltzmann portfolios.

finance - Financial Risk Calculations. Optimized for ease of use through class construction and operator overload.

qfrm - Quantitative Financial Risk Management: awesome OOP tools for measuring, managing and visualizing risk of financial instruments and portfolios.

visualize-wealth - Portfolio construction and quantitative analysis.

VisualPortfolio - This tool is used to visualize the perfomance of a portfolio.

universal-portfolios - Collection of algorithms for online portfolio selection.

FinQuant - A program for financial portfolio management, analysis and optimisation.

Empyrial - Portfolio's risk and performance analytics and returns predictions.
