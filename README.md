# 📈 Quantitative Portfolio Optimization

> A professional-grade portfolio management system built with Modern Portfolio Theory, dynamic rebalancing, and comprehensive risk management.

[![Open Data Collection in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Anz07/portfolio-optimization/blob/main/Data_Collection.ipynb)
[![Open Execution in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Anz07/portfolio-optimization/blob/main/Execution.ipynb)

## 🎯 Project Overview

Constructed and optimized a **7-asset equity portfolio** (CVX, AMD, INTC, JNJ, UNH, JPM, META) using advanced quantitative methods over a 5-day intensive research sprint.

## 🛠️ Key Features

- ✅ **Efficient Frontier** — Markowitz mean-variance optimization
- ✅ **Monte Carlo Simulation** — 10,000+ portfolio simulations
- ✅ **Risk Management** — VaR & CVaR at 90%, 95%, 99% confidence
- ✅ **Stress Testing** — COVID crash, 2008 GFC, rate shock scenarios
- ✅ **Dynamic Rebalancing** — Monthly, quarterly with transaction costs
- ✅ **Risk Parity** — Equal risk contribution portfolio
- ✅ **Performance Attribution** — Rolling Sharpe, drawdown analysis

## 📊 Assets Covered

| Ticker | Company | Sector |
|--------|---------|--------|
| CVX | Chevron | Energy |
| AMD | Advanced Micro Devices | Technology |
| INTC | Intel | Technology |
| JNJ | Johnson & Johnson | Healthcare |
| UNH | UnitedHealth Group | Healthcare |
| JPM | JPMorgan Chase | Financials |
| META | Meta Platforms | Technology |

## 📁 Repository Structure

```
portfolio-optimization/
├── Data_Collection.ipynb    # Data download & EDA
├── Execution.ipynb          # Full optimization pipeline
└── results/                 # Charts & visualizations
```

## 🔑 Key Results

- 📈 **Max Sharpe Portfolio** — Best risk-adjusted returns
- 🛡️ **Min Volatility Portfolio** — Lowest drawdown profile
- ⚖️ **Risk Parity** — Most diversified risk allocation
- 💰 **Dynamic Rebalancing** — Outperformed static buy-and-hold

## 🧰 Tech Stack

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green)
![NumPy](https://img.shields.io/badge/NumPy-1.24-orange)
![SciPy](https://img.shields.io/badge/SciPy-1.10-red)
![yFinance](https://img.shields.io/badge/yFinance-0.2-yellow)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-purple)

## 📚 Methodology

1. **Data Collection** — 5 years of daily price data via yFinance
2. **Statistical Analysis** — Returns, covariance, correlation
3. **Optimization** — Convex optimization via SciPy
4. **Backtesting** — Walk-forward validation 2022–2024
5. **Risk Analysis** — Tail risk, stress scenarios, drawdowns
6. **Rebalancing** — Dynamic strategies with transaction costs

---
*Built as part of a quantitative finance research sprint — July 2026*
