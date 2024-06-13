# Monte-Carlo-for-stock-price-prediction

MSFT Stock Price Simulation and Risk Analysis </br>
Project Overview
This project involves conducting Monte Carlo simulations on historical Microsoft (MSFT) stock data to predict future prices and calculate risk metrics such as Value at Risk (VaR) and Conditional Value at Risk (CVaR). The analysis aims to enhance investment decision-making and risk management strategies.

Features
Data Extraction: Utilizes Yahoo Finance to extract historical stock price data for MSFT.
Statistical Analysis: Calculates historical log returns, mean, variance, and standard deviation.
Monte Carlo Simulations: Generates 10,000 simulations to model potential future stock prices.
Risk Metrics: Calculates and visualizes VaR and CVaR to quantify financial risk.
Visualization: Provides various plots for historical prices, log returns, density distributions, and simulated future prices.
Technologies Used
Python
Libraries: numpy, pandas, yfinance, matplotlib, scipy

Install Required Packages:
Make sure you have numpy, pandas, yfinance, matplotlib, and scipy installed. You can install them using:

sh
Copy code
pip install numpy pandas yfinance matplotlib scipy
Run the Analysis:
Open the Jupyter Notebook or Python script and execute the cells to perform the analysis.

Code Overview
Data Extraction: Retrieves historical stock data for MSFT from Yahoo Finance.
Log Returns Calculation: Computes historical log returns to analyze stock performance.
Monte Carlo Simulation: Runs simulations to predict future stock prices based on historical data.
Risk Analysis: Calculates VaR and CVaR to assess financial risk.
Visualization: Plots various charts to visualize historical data, log returns, and simulation results.
Results
Best, Average, and Worst Case Scenarios: Provides a range of possible future stock prices.
Risk Metrics: Quantifies financial risk using VaR and CVaR.
Confidence Intervals: Offers price ranges within 68% and 95% confidence intervals.
Summary Statistics
The project provides summary statistics of the simulated MSFT prices, including worst case, average case, best case, VaR, CVaR, mean, and standard deviation.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Inspired by financial analysis techniques and quantitative finance principles.
Utilizes historical data from Yahoo Finance.
