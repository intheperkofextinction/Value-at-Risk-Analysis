# Value-at-Risk-Analysis
Portfolio risk assessment using VaR and Monte Carlo simulation
📌 Project Overview

This project analyzes portfolio risk using Value at Risk (VaR) and Monte Carlo Simulation techniques. VaR is a widely used risk measure in finance that estimates the potential loss in portfolio value over a given time period with a certain confidence level.

We implement and compare three VaR methodologies:

Historical VaR – Based on past returns.

Parametric VaR (Variance-Covariance Method) – Assumes normal distribution of returns.

Monte Carlo Simulation – Uses simulations to model potential future losses.

📂 Dataset

Source: Stock market data fetched via yfinance.

Assets Analyzed: [List of stocks/indices used]

Timeframe: [Specify start and end date]

📊 Methodology

1️⃣ Data Collection & Preprocessing

Extract historical stock prices using yfinance

Clean and format data for analysis

Calculate daily returns for each asset

2️⃣ Exploratory Data Analysis (EDA)

Summary statistics (mean, standard deviation, skewness, kurtosis)

Correlation heatmap to assess asset dependencies

Time-series plots of stock prices

3️⃣ Value at Risk (VaR) Calculation

Historical VaR: Uses empirical quantiles of past returns.

Parametric VaR: Uses mean and standard deviation under normality assumptions.

Monte Carlo Simulation: Generates thousands of possible future return scenarios.

4️⃣ Visualization & Analysis

Compare VaR methods with bar charts

Monte Carlo simulated distributions

Portfolio risk assessment based on computed VaR values

💡 Key Insights & Business Application

Historical VaR is simple but heavily dependent on past data trends.

Parametric VaR assumes normality, which may not always hold in volatile markets.

Monte Carlo Simulation provides flexibility but is computationally expensive.

How Financial Firms Can Use This:

Risk managers can use VaR to set portfolio loss limits.

Investors can allocate assets to minimize risk exposure.

Traders can integrate VaR into hedging strategies.


🏆 Future Improvements

Extend Monte Carlo Simulation to include non-normal distributions.

Apply stress testing to simulate extreme market scenarios.
