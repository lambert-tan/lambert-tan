# Hi, I'm Lambert 👋

I'm based in Toronto and studying for a **Master of Management in Analytics at Queen’s University’s Smith School of Business**. My background is in statistics. Before graduate school, I worked with banking clients at RBC and TD. I’m interested in risk and customer analytics, particularly how teams decide which cases need a closer look.

---

## Selected analytics projects

### Toronto Airbnb Pricing Analytics
**15,332 listings · DuckDB · Python · Tableau · Streamlit**

I wanted to know how much location matters for nightly price once you account for the listing itself. I used DuckDB to clean the raw listings, check the sample, and compare median prices by neighbourhood and room type. I then fitted a log-price regression in Python to compare listings with similar characteristics.

Holding the other model inputs constant, entire homes were priced **43.8% higher** than private rooms, while each additional kilometre from Union Station was associated with a **2.7% lower** nightly price. The Tableau dashboard shows the market comparisons, and the Streamlit app lets you change listing details to explore the model estimate.

[Explore the SQL queries](https://github.com/lambert-tan/toronto-airbnb-pricing-analytics#sql-layer-duckdb) · [View the project](https://github.com/lambert-tan/toronto-airbnb-pricing-analytics) · [Open Tableau dashboard](https://public.tableau.com/views/Toronto_Airbnb_Pricing_Analytics/Dashboard01MarketPulse) · [Try the pricing app](https://toronto-airbnb-pricing-analytics-jthhn2unchpj3ewyfbnyfq.streamlit.app/)

### Negative Review Prediction in E-Commerce
**95,824 delivered orders · DuckDB · LightGBM · CatBoost**

How early can a service team spot an order likely to receive a one- or two-star review? I used SQL to build one record per order, aggregating items and payments before joining them so that larger baskets wouldn’t count more than once. I then compared two models using only the information available when an order was placed or delivered.

On the test set, the placement model had a ROC-AUC of **0.658**. The delivery model, which could also use shipping and delivery times, reached **0.775**. The highest-risk 10% of orders accounted for **43.6% of negative reviews** in the test set. A service team could use that ranking to prioritize follow-up.

[Explore the SQL queries](https://github.com/lambert-tan/olist-negative-review-prediction#sql-pipeline-duckdb) · [View the project](https://github.com/lambert-tan/olist-negative-review-prediction)

### Toronto Warming Centre Optimization
**7 centres · Python · Monte Carlo simulation · Integer optimization**

Our graduate team studied how Toronto could allocate staff and beds across seven warming centres. For this portfolio, I rebuilt the demand simulation and tested the team’s 19-person staffing plan across 5,000 nights.

Under the model’s staffing ratio, every centre had enough staff for its existing beds. In the original extreme-demand scenario, **297 of 306 people** were admitted. The team’s expansion analysis placed five additional beds each at Elizabeth and Scarborough, where the existing shifts could cover them.

[View the project](https://github.com/lambert-tan/toronto-warming-centre-optimization)

---

## Toolkit

**Analytics:** `SQL (DuckDB)` · `Python` · `pandas` · `NumPy` · `scikit-learn` · `Statsmodels`  
**Visualization & delivery:** `Tableau` · `Streamlit` · `Excel`  
**Methods:** regression · classification · clustering · model validation · Monte Carlo simulation · optimization

---

## A little more about me

Outside work, I like exploring Toronto, travelling, and spending time with my Chihuahua, Amiu.

### Currently

🎓 Master of Management in Analytics — **Smith School of Business, Queen's University**  
🔎 Exploring opportunities in **business analytics, data analytics, customer analytics, and risk analytics**  
📍 Toronto, Canada

---

## Connect

**LinkedIn:** [linkedin.com/in/lamberttan](https://www.linkedin.com/in/lamberttan/) · **Email:** [tanjianglin845@gmail.com](mailto:tanjianglin845@gmail.com)
