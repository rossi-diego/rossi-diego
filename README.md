# Diego Rossi

**Market Risk Manager · Commodity pricing, derivatives & risk modelling · Python**

I run market risk at **Inpasa**, a leading Brazilian corn ethanol producer, covering physical grain, exchange-traded futures and FX. I build the Python tooling behind that work: position consolidation, risk metrics and quantitative models.

The repositories here rebuild that workflow on public data. They contain no employer data.

## What I work on

- **Markets:** corn, ethanol and DDGS; the soy complex; BRL FX and rates
- **Instruments:** physical forwards, CBOT and B3 futures and options, NDFs
- **Risk:** VaR and Expected Shortfall and their backtests, stress testing, hedge effectiveness, basis risk
- **Forecasting:** point-in-time backtests, with prediction ranges checked against what actually happened
- **Data:** pipelines for market fundamentals and prices, from raw source files to published, versioned data

## Projects

| Project | What it does | Stack |
|---|---|---|
| [**Soybean crush margin**](https://github.com/rossi-diego/soybean-crush-margin) · [live app](https://soybean-crush-margin.streamlit.app/) | Daily soybean crush margin, oil share of product value and soybean oil feedstock cost against heating oil, with and without the D4 RIN, from CBOT and NYMEX futures. 1-day VaR 95% and ES 97.5% by filtered historical simulation (EWMA volatility), with Euler ES allocation by leg. Over 5 years the filtered VaR passes the Kupiec and Christoffersen tests (4.8% exceptions); plain historical simulation fails both. ES is backtested with Acerbi–Székely. Roll and delivery sessions are left out of every statistic | Python · pandas · Plotly · Streamlit · pytest · mypy · GitHub Actions |
| [**Soy Outlook**](https://github.com/rossi-diego/soy-outlook) · [live site](https://soy-outlook.vercel.app) | Brazilian (Paranaguá FOB) soybean price-risk ranges 1, 3 and 6 months after each USDA WASDE, from a point-in-time backtest since 2010 with model selection fixed in advance. No model beat "no change", so the site shows ranges labelled by how often they held, plus a hedging calculator, in English and Portuguese | Python · pandas · statsmodels · scikit-learn · Next.js / TypeScript · Playwright · GitHub Actions · Vercel |
| [**USDA Reports Dashboard**](https://github.com/rossi-diego/usda-reports-dashboard) · [live site](https://usda-reports.vercel.app) | Five USDA reports (every WASDE since July 2010, Export Sales, NASS crush, Crop Progress and Grain Stocks) harmonised into one point-in-time data product. It is rebuilt automatically on release day, checked by dbt data tests and published as versioned downloads and a dashboard in English and Portuguese | Python · DuckDB · dbt · Docker · GitHub Actions · Next.js / TypeScript |

## Stack

Python (pandas, NumPy, statsmodels, scikit-learn) · SQL · DuckDB · dbt · Docker · pytest · mypy · ruff · GitHub Actions · Next.js / TypeScript

## Languages

Portuguese (native) · English (full professional proficiency)

## Contact

[LinkedIn](https://www.linkedin.com/in/diego-rossi-santanna)
