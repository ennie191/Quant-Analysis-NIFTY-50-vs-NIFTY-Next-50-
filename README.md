Quantitative Analysis: NIFTY 50 vs NIFTY Next 50

This project performs a quantitative comparison of the performance of NIFTY 50 and NIFTY Next 50 over the last decade (2015–2025).

The project is inspired by the Bank of America Global Research theme of “innovation arbitrage”, which suggests that innovation-focused investments may outperform traditional market indices.

This notebook adapts that idea to the Indian public market by comparing:

NIFTY 50 ETF (NIFTYBEES) — representing the mature market
NIFTY Next 50 ETF (JUNIORBEES) — representing the innovation basket
Project Objective

The goal of this analysis is to determine whether the innovation-focused index delivered better risk-adjusted returns compared to the broader market.

Methodology

The project follows these steps:

Data Collection
Historical ETF price data was obtained for:
NIFTYBEES.NS
JUNIORBEES.NS
Data Cleaning
Outliers in the dataset were identified and removed to ensure accurate return calculations.
Return Calculation
Daily returns were computed for both ETFs.
Performance Metrics
The following financial metrics were calculated:
CAGR (Compound Annual Growth Rate)
Annualized volatility
Sharpe ratio
Rolling Volatility Analysis
3-year rolling volatility was calculated to study how risk changed over time.
Key Findings

The analysis revealed that:

NIFTY Next 50 had slightly higher raw returns
However, NIFTY Next 50 also had significantly higher volatility
As a result, NIFTY 50 delivered better risk-adjusted returns

Final metrics from the analysis:

Metric	NIFTY 50	NIFTY Next 50
CAGR	13.56%	14.19%
Volatility	14.71%	17.03%
Sharpe Ratio	0.58	0.54

These results suggest that the higher return of the innovation basket was not sufficient to compensate for the additional risk.

Technologies Used
Python
Pandas
NumPy
Matplotlib
yfinance
Google Colab
Output Visualizations

The notebook generates:

Growth of ₹1 invested over 10 years
Rolling 3-year volatility comparison
Risk vs return metrics

These visualizations help illustrate the difference between raw performance and risk-adjusted performance.
