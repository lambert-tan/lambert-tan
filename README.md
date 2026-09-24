# Hi, I'm Lambert

I'm currently completing a **Master of Management in Analytics at Queen's University**. My background is in Statistics, and I previously worked in client-facing banking roles at RBC and TD before moving into business analytics.

I'm interested in using data to understand business problems rather than treating modelling as an end in itself. Most of my projects start with a practical question, then work through data preparation, modelling, evaluation, and interpretation.

## Skills & Projects

| Area | Project | Methods & Tools |
|---|---|---|
| **Python / Machine Learning** | [Negative Review Prediction in E-Commerce](https://github.com/lambert-tan/olist-negative-review-prediction) | Python, pandas, scikit-learn, LightGBM, CatBoost, K-Means, Optuna |
| **Statistical Modelling** | Toronto Airbnb Pricing Analysis | OLS, log-price regression, feature engineering, model diagnostics |
| **Optimization** | Toronto Warming Centre Optimization | Python, Monte Carlo simulation, MILP |
| **SQL / Risk Analytics** | Credit Risk Analysis | SQL, R, logistic regression, ROC-AUC |
| **Data Visualization** | Toronto Airbnb Pricing Analysis | Tableau, Python |

I am gradually adding the underlying work for these projects to GitHub as I clean up the code and documentation.

## Featured Project

### [Predicting Negative Customer Reviews in Brazilian E-Commerce](https://github.com/lambert-tan/olist-negative-review-prediction)

This project looks at a simple question: **how early can an e-commerce platform identify an order that is likely to receive a negative review?**

I used **95,824 orders from the Olist Brazilian e-commerce dataset** and built models at two points in the order lifecycle. The placement-stage model uses information available when an order is placed, while the delivery-stage model adds information about the actual fulfilment process.

The final LightGBM placement model achieved an **F1 score of 0.318** and **ROC-AUC of 0.677**. After delivery information became available, the CatBoost model improved to an **F1 score of 0.484** and **ROC-AUC of 0.768**. I also used K-Means clustering to examine groups of orders with different review-risk patterns.

The comparison is useful because the later model is more accurate, but the earlier model leaves more time to intervene. For me, that trade-off was more interesting than simply choosing the model with the higher score.

## Technical Skills

**Languages:** Python · SQL · R  
**Analytics and ML:** pandas · NumPy · scikit-learn · Statsmodels · LightGBM · CatBoost  
**Visualization:** Tableau · Matplotlib · Excel  
**Methods:** Regression · Classification · Clustering · Monte Carlo Simulation · MILP  
**Other:** Git · GitHub · PowerPoint

## Background

**Queen's University — Smith School of Business**  
Master of Management in Analytics

**BSc in Statistics**

My previous banking experience gave me a strong interest in customer behaviour, risk, and the way analytical results are used in day-to-day decisions. I am now building on that experience through graduate coursework and applied analytics projects.

## Connect

I'm based in Toronto and currently exploring opportunities in business analytics, data analytics, customer analytics, and risk analytics.
