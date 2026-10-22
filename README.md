# Hi, I'm Karan

BSc International Politics & Government (Bocconi University, Milan; exchange at ESADE, Barcelona), building a data analytics and applied machine learning portfolio.

I like questions where economics, data and a decision meet: what drives a price, did a promotion actually work, which result still holds when you test it.

## Projects

| Project | What it does | Stack |
|---|---|---|
| [Promotion uplift analysis](https://github.com/karanbaylav/promo-uplift-sql) | Do in-store display weeks raise sales, and are they worth it? Compares stores with and without displays on a 31.9M-row product × store × week table, with placebo and pre-trend checks. Display weeks lift sales by about 30–55% (a range, since sales were already rising the week before), with no evidence of a dip afterwards | SQL (DuckDB), Python |
| [Milan Airbnb market analysis](https://github.com/karanbaylav/milan-airbnb-sql-analysis) | Compares three Inside Airbnb snapshots (2019, Dec 2025, Sep 2026; ~59K listings) with a tested SQL pipeline and rules written before the analysis. Superhosts get ~2.9x the bookings of comparable listings (replicated on a second snapshot); pricing 2x above peers goes with 40% fewer bookings | SQL (DuckDB: CTEs, window functions, QUALIFY), Python (statsmodels OLS) |
| [The Profit Curve](https://github.com/karanbaylav/profit-curve-bank-profitability) | Tests whether U.S. bank profitability is a nonlinear (inverted-U) function of the Federal Funds Rate on ~640K bank-quarter observations, 2001–2023 | Python, panel fixed effects, Lasso, Gradient Boosting, SHAP |
| [What sets the price of a Barcelona flat?](https://github.com/karanbaylav/barcelona-housing-price-ml) | Explains and predicts ~46K Idealista asking prices: hedonic regression vs Random Forest vs XGBoost (R² 0.84 → 0.91 on held-out flats), with SHAP showing the non-linear centre premium | Python, statsmodels, scikit-learn, XGBoost, SHAP |

Next: financial valuation models (DCF, comparables, LBO).

## Toolkit

- **Languages:** SQL (DuckDB; CTEs, window functions), Python (pandas, NumPy, scikit-learn, XGBoost, statsmodels), Stata, R
- **Data and BI tools:** Tableau, Power BI, Microsoft Excel
- **Background:** quantitative social science, econometrics, research design

## Contact

[LinkedIn](https://www.linkedin.com/in/karan-baylav)
