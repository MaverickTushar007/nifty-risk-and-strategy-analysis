# NIFTY 50 Risk and Strategy Analysis

## Overview
This project analyzes daily NIFTY 50 price data to understand how returns and risk behave over time using basic time-series techniques. The focus is on volatility dynamics, drawdowns, and risk-adjusted performance rather than return prediction.

## Data
Daily closing price data for the NIFTY 50 index.

## Methodology
- Constructed daily log returns from price data
- Analyzed return distributions and tail behavior
- Studied volatility clustering and time-varying risk
- Implemented a simple rule-based time-series momentum strategy
- Evaluated performance using cumulative wealth, drawdowns, transaction costs, and Sharpe ratio

## Key Findings
- Daily returns are noisy and difficult to predict
- Volatility exhibits clustering and persistence, indicating time-varying market risk
- Simple rule-based strategies can significantly reduce drawdowns
- Long-term performance is driven more by risk management than return prediction

## Conclusion
The analysis demonstrates that systematic decision rules and downside protection play a crucial role in sustainable compounding. Even simple strategies can improve portfolio survivability by controlling drawdowns, despite not consistently outperforming buy-and-hold in total returns.
