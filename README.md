# 📈 Quantitative Portfolio Optimization
**Phase 2 | Modern Portfolio Theory | July 2026**

---

## 🎯 Overview
Applied **Markowitz Modern Portfolio Theory (MPT)** to construct 
an optimal, risk-adjusted portfolio across 7 equity assets using 
Python. Built a full quantitative pipeline from data collection 
to dynamic rebalancing with transaction cost modeling.

**Assets:** CVX | AMD | INTC | JNJ | UNH | JPM | META  
**Period:** 2019–2025 (Training: 2019–2022 | Test: 2022–2025)

---

## 📊 Key Results

| Strategy | Ann. Return | Volatility | Sharpe Ratio | Max Drawdown |
|---|---|---|---|---|
| ⭐ Max Sharpe | 12.52% | 18.99% | 0.396 | -21.34% |
| Min Volatility | 6.53% | 15.87% | 0.097 | -22.29% |
| Equal Weight | 6.07% | 20.75% | 0.052 | -30.36% |
| Risk Parity | 5.70% | 19.27% | 0.036 | -29.19% |

---

## 🏆 Final Recommendation
**70% Max Sharpe + 30% Min Volatility blend**  
Rebalancing: Quarterly | Transaction Cost: 10bps per trade

| Asset | Weight | Role |
|---|---|---|
| AMD | ~28% | Growth |
| JNJ | ~18% | Defensive |
| UNH | ~16% | Defensive |
| META | ~11% | Growth |
| INTC | ~10% | Value/Tech |
| CVX | ~9% | Value/Dividend |
| JPM | ~8% | Cyclical |

---

## 🔬 Methodology
- ✅ Efficient Frontier — 10,000 Monte Carlo simulations
- ✅ Convex Optimization — SLSQP solver (scipy)
- ✅ Risk Metrics — VaR & CVaR at 95%/99% confidence
- ✅ Stress Testing — COVID crash, 2022 rate hikes, GFC
- ✅ Dynamic Rebalancing — Monthly/Quarterly/Annual
- ✅ Transaction Cost Modeling — 10bps per rebalance

---

## 🛠️ Tech Stack
| Tool | Purpose |
|---|---|
| Python 3.10 | Core language |
| yfinance | Market data collection |
| numpy / pandas | Data manipulation |
| scipy | Portfolio optimization |
| matplotlib / seaborn | Visualizations |
| Google Colab | Development environment |

---

*Built as part of a structured quantitative finance 
self-study program | July 2026
