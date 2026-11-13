# Diego Rossi

**Market Risk Manager · Commodity pricing, derivatives & risk modelling · Python**

I run market risk at **Inpasa**, a leading Brazilian corn ethanol producer, covering physical grain, exchange-traded futures and FX. I build the Python tooling behind that work: position consolidation, risk metrics and quantitative models.

All projects use public market data.

## What I work on

- **Markets:** corn, ethanol and DDGS; the soy complex; BRL FX and rates
- **Instruments:** physical forwards, CBOT and B3 futures and options, NDFs
- **Risk:** VaR and Expected Shortfall and their backtests, stress testing, hedge effectiveness, basis risk
- **Forecasting:** point-in-time backtests, with prediction ranges checked against what actually happened
- **Data:** pipelines for market fundamentals and prices, from raw source files to published, versioned data

## Projects

| Project | What it does | Stack |
|---|---|---|
| [**Soybean crush margin**](https://github.com/rossi-diego/soybean-crush-margin) · [live app](https://soybean-crush-margin.streamlit.app/) | Tracks the daily soybean crush margin and biodiesel feedstock costs from CBOT and NYMEX futures, with Value at Risk and Expected Shortfall backtested over 5 years | Python · pandas · Plotly · Streamlit · pytest · mypy · GitHub Actions |
| [**Soy Outlook**](https://github.com/rossi-diego/soy-outlook) · [live site](https://soy-outlook.vercel.app) | Price-risk ranges for Brazilian soybeans 1, 3 and 6 months after each USDA WASDE report, tested against what actually happened since 2010, plus a hedging calculator | Python · pandas · statsmodels · scikit-learn · Next.js / TypeScript · Playwright · GitHub Actions · Vercel |
| [**USDA Reports Dashboard**](https://github.com/rossi-diego/usda-reports-dashboard) · [live site](https://usda-reports.vercel.app) | Five USDA crop reports in one clean dataset, most going back to 2010, updated automatically on release day, with a dashboard and downloads | Python · DuckDB · dbt · Docker · GitHub Actions · Next.js / TypeScript |

## Stack

Python (pandas, NumPy, statsmodels, scikit-learn) · SQL · DuckDB · dbt · Docker · pytest · mypy · ruff · GitHub Actions · Next.js / TypeScript

## Languages

Portuguese (native) · English (full professional proficiency)

## Contact

[LinkedIn](https://www.linkedin.com/in/diego-rossi-santanna)
