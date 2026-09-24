# Hi, I'm Lambert

I'm a **Master of Management in Analytics candidate at Queen's University** with a background in Statistics and client-facing banking experience at RBC and TD.

I became interested in analytics through a simple question: **what does the data actually say, and how should that change a business decision?** Most of my work follows that logic—from cleaning and modelling to validation, interpretation, and communicating the result in a form that someone can actually use.

## Selected Projects

| Project | Question | Methods |
|---|---|---|
| [Toronto Airbnb Pricing Analytics](https://github.com/lambert-tan/toronto-airbnb-pricing-analytics) | Which listing characteristics are most strongly associated with nightly price in Toronto? | Python, pandas, Statsmodels, log-price OLS, HC3 robust inference, Streamlit |
| [Negative Review Prediction in E-Commerce](https://github.com/lambert-tan/olist-negative-review-prediction) | How early can an e-commerce business identify orders at risk of receiving a negative review? | Python, scikit-learn, LightGBM, CatBoost, K-Means |
| [Toronto Warming Centre Optimization](https://github.com/lambert-tan/toronto-warming-centre-optimization) | How should limited staffing and bed capacity be allocated under uncertain winter demand? | Excel Solver, Python, Monte Carlo simulation, optimization |

## Toronto Airbnb Pricing Analytics

I analyzed **15,332 Toronto Airbnb listings** to separate the effects of property characteristics, location, and booking features on nightly price.

The final log-price model explains about **61.8% of variation in the test sample**. Entire-home status and bathroom arrangement showed much larger pricing differences than smaller operational features such as instant booking or amenity count.

I also rebuilt the analysis as a reproducible Python workflow and developed a small Streamlit application for exploring model-implied pricing scenarios.

[View repository](https://github.com/lambert-tan/toronto-airbnb-pricing-analytics) · [Open live app](https://toronto-airbnb-pricing-analytics-jthhn2unchpj3ewyfbnyfq.streamlit.app/)

## Negative Review Prediction in E-Commerce

Using **95,824 orders from the Olist Brazilian e-commerce dataset**, I built classification models at two stages of the order lifecycle.

The placement-stage LightGBM model achieved an **F1 score of 0.318** and **ROC-AUC of 0.677**. After delivery information became available, the CatBoost model improved to an **F1 score of 0.484** and **ROC-AUC of 0.768**.

The more useful finding was the timing trade-off: the later model was more accurate, but the earlier model gave the business more time to intervene.

[View repository](https://github.com/lambert-tan/olist-negative-review-prediction)

## Toronto Warming Centre Optimization

This project examines how staffing and bed capacity can be allocated across seven Toronto warming centres under uncertain demand.

The optimization allocated **19 staff** across a network with **301 physical beds**. Under the model assumptions, bed capacity became the binding operational constraint. I then used a **5,000-iteration Monte Carlo simulation** to stress-test the allocation and compare alternative expansion options.

[View repository](https://github.com/lambert-tan/toronto-warming-centre-optimization)

## Technical Toolkit

**Python:** pandas, NumPy, scikit-learn, Statsmodels, LightGBM, CatBoost  
**Analytics:** regression, classification, clustering, model validation, Monte Carlo simulation, optimization  
**Other tools:** SQL, R, Excel, Tableau, PowerPoint, Git, GitHub

## Background

**Queen's University — Smith School of Business**  
Master of Management in Analytics

**BSc in Statistics**

Before moving into analytics, I worked in client-facing banking roles at **RBC and TD**. That experience is still useful in the way I approach analytical work: I care about the model, but I also care about whether the result is understandable, relevant, and usable in a real decision.

## Currently

Based in Toronto and exploring opportunities in **business analytics, data analytics, customer analytics, and risk analytics**.
