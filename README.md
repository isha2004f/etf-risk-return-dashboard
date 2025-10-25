# ETF Risk–Return Dashboard

This project analyzes the performance of six ETFs — **SPY, QQQ, XLV, XLE, VNQ, ICLN** — using Python and Excel.  
It automates data retrieval, computes core portfolio metrics, and renders presentation-ready visuals.

---

## Features
- Automated data download from Yahoo Finance via `yfinance`
- Calculations:
  - Daily returns
  - Annualized return & volatility (252 trading days)
  - Sharpe ratio (configurable risk-free rate)
  - Correlation matrix
- Visualizations:
  - **Risk–Return Scatter** (Volatility vs. Return)
  - **Sharpe Ratio by ETF**
  - **Correlation Heatmap**
  - **Efficient Frontier** (random portfolios + max Sharpe highlight)
- Excel dashboard template for quick reporting

---

## Tech Stack
- **Python:** pandas, numpy, yfinance, matplotlib
- **Excel:** interactive charts & formulas
- **Environment:** Jupyter Notebook / VS Code

---

## Project Structure
etf-risk-return-dashboard/
├── etf_dashboard.ipynb
├── ETF_Dashboard_Template.xlsx
├── prices_etf.csv
├── returns_etf.csv
├── metrics_etf.csv
├── correlations_etf.csv
├── risk_return_scatter.png
├── sharpe_by_etf.png
├── correlations_etf_heatmap.png
└── efficient_frontier.png

---

## How to Run

1. **Install dependencies**
   ```bash
   pip install pandas numpy yfinance matplotlib
   
---
   
## License
MIT
