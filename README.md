# Hi, I'm Lambert 👋

### I like turning messy data into answers people can actually use.

I'm a **Master of Management in Analytics candidate at Queen's University** with a background in **Statistics** and client-facing banking experience at **RBC and TD**.

I moved into analytics because I enjoy the part between *“we have data”* and *“so what should we do?”* Most of my projects start with a business question and then work through the data, modelling, validation, and interpretation needed to answer it.

📍 Toronto · 📊 Business & Data Analytics · 🐶 Usually working with my Chihuahua, Amiu, nearby

---

## Selected analytics projects

My projects cover **pricing, customer risk, and resource allocation**, using SQL (DuckDB), regression, machine learning, simulation, optimization, dashboards, and lightweight deployment.

### 🏙️ Toronto Airbnb Pricing Analytics
**15,332 listings · Regression · Tableau · Streamlit**

**Question:** What actually drives Airbnb prices in Toronto?

I built a reproducible pricing analysis using a log-price OLS model, feature engineering, an interactive Tableau workbook, and a Streamlit pricing tool. The final model achieved **test R² = 0.619**. Property format and bathroom setup were associated with larger price differences than smaller operational features.

In DuckDB, I clean the listing data, check the model inputs, and compare median nightly prices across neighbourhoods, room types, and distance bands.

[Listing preparation](https://github.com/lambert-tan/toronto-airbnb-pricing-analytics/blob/main/sql/01_clean_and_engineer.sql) · [Quality checks](https://github.com/lambert-tan/toronto-airbnb-pricing-analytics/blob/main/sql/02_quality_checks.sql) · [Market queries](https://github.com/lambert-tan/toronto-airbnb-pricing-analytics/blob/main/sql/03_market_exploration.sql)

[View the project](https://github.com/lambert-tan/toronto-airbnb-pricing-analytics) · [Open Tableau dashboard](https://public.tableau.com/views/Toronto_Airbnb_Pricing_Analytics/Dashboard01MarketPulse) · [Try the pricing app](https://toronto-airbnb-pricing-analytics-jthhn2unchpj3ewyfbnyfq.streamlit.app/)

### 🛒 Negative Review Prediction in E-Commerce
**95,824 orders · Classification · CatBoost · LightGBM**

**Question:** How early can a business identify an order that is likely to end in a negative review?

I compared risk models at two points in the order lifecycle. The LightGBM placement model gives the business more time to respond, while the delivery-stage CatBoost model is more selective and reaches **ROC-AUC 0.768**. I use the comparison to show how model timing affects the type of action a business can take.

I use SQL to aggregate items and payments before joining them to orders, so each delivered order counts once. I then compare negative-review rates by delivery timing and measure how many negative reviews fall in the highest-risk score deciles.

[Order joins](https://github.com/lambert-tan/olist-negative-review-prediction/blob/main/sql/01_build_master_orders.sql) · [Reconciliation checks](https://github.com/lambert-tan/olist-negative-review-prediction/blob/main/sql/02_quality_checks.sql) · [Risk queries](https://github.com/lambert-tan/olist-negative-review-prediction/blob/main/sql/03_risk_analysis.sql) · [Scorecard metrics](https://github.com/lambert-tan/olist-negative-review-prediction/blob/main/sql/04_scorecard_metrics.sql)

[View the project](https://github.com/lambert-tan/olist-negative-review-prediction)

### ❄️ Toronto Warming Centre Optimization
**7 centres · Monte Carlo simulation · Integer optimization · Decision analytics**

**Question:** How should limited staffing and bed capacity be allocated when winter demand is uncertain?

I combined optimization with a **5,000-night Monte Carlo stress test** under a **$33,000 nightly budget**. The optimized plan allocates **19 staff**. At that level, staff can support 380 clients, compared with **301 physical beds**, so bed capacity becomes the tighter constraint under high demand.

[View the project](https://github.com/lambert-tan/toronto-warming-centre-optimization)

---

## Toolkit

**Analytics:** `SQL (DuckDB)` · `Python` · `pandas` · `NumPy` · `scikit-learn` · `Statsmodels`  
**Visualization & delivery:** `Tableau` · `Streamlit` · `Excel`  
**Methods:** regression · classification · clustering · model validation · Monte Carlo simulation · optimization

---

## A little more about me

Before analytics, I worked in client-facing banking at **RBC and TD**. That experience is one reason I tend to look at analytics from the business side. I care about the model, but also about whether the result is understandable and useful to the person making the decision.

Outside the notebook, I’m usually exploring Toronto, travelling, or spending time with my Chihuahua.

### Currently

🎓 Master of Management in Analytics — **Smith School of Business, Queen's University**  
🔎 Exploring opportunities in **business analytics, data analytics, customer analytics, and risk analytics**  
📍 Toronto, Canada

---

## Connect

I'm always happy to connect with people working in analytics, banking, or data-driven decision-making.

**LinkedIn:** [linkedin.com/in/lamberttan](https://www.linkedin.com/in/lamberttan/) · **Email:** [tanjianglin845@gmail.com](mailto:tanjianglin845@gmail.com)
