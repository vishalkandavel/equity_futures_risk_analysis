# Equity vs Equity Futures Risk Analysis

## Overview

This project analyzes the relationship between equity prices and equity futures contracts using two Indian listed companies - **Marico Ltd.** and **Zydus Lifesciences Ltd.**

The objective is to evaluate how futures instruments behave relative to their underlying equities in terms of returns, volatility, liquidity, and risk-adjusted performance across multiple time horizons.

The study provides insights into derivatives market efficiency and investment decision-making between spot and futures exposure.

## Key Objectives

- Compare equity and futures return characteristics across instruments
- Evaluate risk-adjusted performance using Sharpe ratios
- Analyze contract maturity effects (near, middle, far month)
- Study liquidity differences between equity and futures markets
- Identify contango/backwardation structure in futures pricing
- Interpret investment implications across time horizons

## Methodology

The analysis was conducted using historical data over the period **April 2024 - March 2025** across multiple frequencies:

- Daily
- Weekly
- Monthly

Instruments analyzed:

- Spot Equity
- Near-Month Futures
- Middle-Month Futures
- Far-Month Futures

Risk-adjusted returns were computed using Treasury Bill rates as the proxy for the risk-free rate.

## Key Findings

### 1. Equity Outperforms Futures on a Risk-Adjusted Basis

Across most timeframes, equity instruments delivered higher Sharpe ratios than futures contracts, indicating better compensation per unit of risk.

### 2. Holding Period Matters

Risk-return efficiency improves with longer investment horizons, with monthly returns showing the strongest performance relative to volatility.

### 3. Futures Maturity Effects

Longer-dated futures contracts exhibit:

- Higher volatility
- Lower liquidity
- Reduced risk-adjusted returns

Near-month contracts generally perform better among derivatives.

### 4. Liquidity Differences

Equity markets demonstrate deeper liquidity compared to futures contracts, while liquidity declines significantly as contract maturity increases.

### 5. Market Structure (Contango)

The futures term structure shows mild contango, with longer-maturity contracts priced slightly higher than near-term contracts, reflecting cost-of-carry and market expectations.

## Strategic Implications

- **Long-term investors:** Direct equity exposure is generally superior.
- **Short-term traders / hedgers:** Near-month futures provide tactical flexibility.
- **Long-dated futures:** Offer limited additional reward relative to risk.

## Repository Contents

```
equity-futures-risk-analysis/
│── equity_futures_analysis.pdf
│── README.md
```

## Applications

- Derivatives trading strategy evaluation
- Hedging and risk management
- Portfolio allocation decisions
- Financial econometrics research
- Market microstructure analysis

## Author

Vishal K  
BITS Pilani Hyderabad  
Finance | Machine Learning | Quantitative Finance Enthusiast
