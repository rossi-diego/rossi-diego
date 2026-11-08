# Diego Rossi

**Market Risk Manager · Commodities, Biofuels & FX · Python risk & data engineering**

I run market risk at **Inpasa**, Latin America's largest corn-ethanol producer, covering physical grain, exchange-traded futures and FX. I build the Python tooling behind that work: position consolidation, risk metrics and quantitative models.

The repositories here rebuild that workflow on public or synthetic data. They contain no employer data.

## What I work on

- **Markets:** corn, ethanol and DDGS; the soy complex; BRL FX and rates
- **Instruments:** physical forwards, CBOT and B3 futures and options, NDFs
- **Risk:** VaR and Expected Shortfall, stress testing, hedge effectiveness, basis risk
- **Forecasting:** point-in-time backtests, prediction ranges checked against what happened
- **Data:** pipelines for market fundamentals and prices, from raw source to served API

## Projects

| Project | What it does | Stack |
|---|---|---|
| [**Soy Outlook**](https://github.com/rossi-diego/soy-outlook) · [live site](https://soy-outlook.vercel.app) | Brazilian (Paranaguá FOB) soybean price-risk ranges 1, 3 and 6 months after each USDA WASDE, from a point-in-time backtest since 2010 with model selection fixed in advance; no model beat "no change", so the site shows ranges labelled by how often they held, plus a hedging calculator, in English and Portuguese | Python · pandas · statsmodels · scikit-learn · Next.js / TypeScript · Playwright · GitHub Actions · Vercel |
| [**Soybean crush margin**](https://github.com/rossi-diego/soybean-crush-margin) · [live app](https://soybean-crush-margin.streamlit.app/) | Daily soybean crush margin, oil share of product value and soybean oil feedstock cost against heating oil, with and without the D4 RIN, from CBOT and NYMEX futures; roll and delivery sessions are left out of every statistic | Python · pandas · Plotly · Streamlit · pytest · GitHub Actions |
| [**USDA fundamentals pipeline**](https://github.com/rossi-diego/wasde-monthly-report) | Medallion pipeline (bronze → silver → gold) for USDA PSD, WASDE, NOPA crush and export sales, with vintage-aware WASDE revision tracking | Python · Airflow · DuckDB · FastAPI · GitHub Actions |

### In progress

- **Market risk platform**: position-to-risk engine for an agri-industrial book (physical, CBOT, basis, BRL FX), with VaR, ES and full-revaluation stress driven by booked positions
- **Commodity VaR backtesting**: model validation for grain, ethanol and BRL portfolios (historical, filtered HS, EWMA, GARCH-t; Kupiec, Christoffersen, ES backtest)

## Stack

Python · pandas · Airflow · FastAPI · DuckDB · PostgreSQL · Docker · GitHub Actions · Next.js / TypeScript

## Languages

Portuguese (native) · English (professional)

## Contact

[LinkedIn](https://www.linkedin.com/in/rossi-diego)
