## Portfolio Management: Multi-Asset Allocation & Insurance Strategies

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white)](https://www.r-project.org/)

Comprehensive application of Modern Portfolio Theory—comparing GMV, PCA, Tangency, Black-Litterman, and CPPI/OBPI across equities and multi-asset classes.

Four research grade methodologies applied to 10 US mega cap tech stocks (AAPL, MSFT, GOOGL, AMZN, TSLA, NVDA, PYPL, CMCSA, ADBE, ASML) and five ETF trackers (VTI, EMGF, IEF, DBC, GLD). (1) GMV portfolio minimizes variance via unbiased covariance estimation and produces counterintuitive short positions (e.g., -50% AAPL) optimal for risk control. (2) PCA reveals latent factors driving asset returns; decomposition into PC1 (market-wide) + PC2 (growth) + PC3 (idiosyncratic risk). (3) Tangency portfolio maximizes risk-adjusted returns using CAPM equilibrium. (4) Black-Litterman incorporates manager views (from BlackRock/Goldman/JPMorgan macro forecasts) to blend market implied returns with subjective beliefs. (5) CPPI & OBPI test dynamic portfolio insurance via Monte Carlo simulation (10,000 trials): CPPI outperforms on Sharpe ratio (0.617 vs 0.34 raw equity) by adjusting exposure to a predetermined floor.

Tech: R (tidyverse, quantmod, ggplot2) | Data: Yahoo Finance 2019–2023 (pre/post-COVID) | Output: Portfolio weights, risk metrics, Sharpe ratios, sensitivity analysis
