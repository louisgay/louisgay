# Hi, I'm Louis

**Quantitative Finance & Software Engineering** — building tools for derivatives pricing, systematic trading, and portfolio construction.

---

## Featured Projects

### [Quant Apps](https://github.com/louisgay/quant-apps) — Interactive Financial Engineering

Three Streamlit applications for structured products, volatility, and portfolio management:

| App | What It Does | Key Technique |
|-----|-------------|---------------|
| **Structured Product Factory** | Prices Autocallable Phoenix & Athena (worst-of) | Monte Carlo + Cholesky, Greeks, correlation risk |
| **Vol Surface Calibrator** | Calibrates SVI implied volatility surfaces | Gatheral no-arbitrage, Brent IV solver |
| **Portfolio Optimizer** | Multi-asset allocation + backtesting | Markowitz, Risk Parity, Black-Litterman |

> 100+ unit tests | Docker-ready | Live market data

---

### [Alpha Engine](https://github.com/louisgay/alpha-engine) — Systematic Trading Framework

Production-grade trading infrastructure connected to Interactive Brokers:

| Module | Description |
|--------|-------------|
| **Features** | Kalman filters, Hawkes process, HMM regime detection — all O(1) streaming |
| **Models** | XGBoost + PyTorch ensembles with isotonic calibration |
| **Risk** | VaR (Historical, Student-t, GARCH), drawdown circuit breaker |
| **Execution** | Kelly sizing, slippage modeling, IBKR live/paper trading |

> Walk-forward backtesting | Async IBKR integration | YAML-configured

---

### [Quant Research](https://github.com/louisgay/quant-research) — Strategy Development & Overfitting Diagnostics

Research notebooks and strategies with rigorous validation:

| Project | Domain | Technique |
|---------|--------|-----------|
| **Cross-Sectional L/S** | Equity | 50-stock long/short with IC-based feature selection |
| **Butterfly Strategy** | Fixed Income | DV01-neutral yield curve trades with PCA |
| **Credit Spread Study** | Credit/Macro | Lead-lag analysis, Granger causality, cointegration |
| **VaR Model Comparison** | Risk | 6 VaR models backtested (Historical to GARCH-t) |
| **Overfitting Audit** | Methodology | CPCV, PBO (de Prado), parameter sensitivity |

> Anti-overfitting focus: Generalization gap, PBO < 20%, parameter stability > 2.0

---

## Tech Stack

`Python` `NumPy` `SciPy` `XGBoost` `PyTorch` `Streamlit` `Plotly` `Docker` `Interactive Brokers` `yfinance`

---

## Contact

<!-- Add your links here -->
- LinkedIn: https://www.linkedin.com/in/louisgay/
- Email: miraca742@gmail.com
