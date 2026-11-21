# Hi, I'm Lambert 👋

### I like turning messy data into answers people can actually use.

I'm a **Master of Management in Analytics candidate at Queen's University** with a background in **Statistics** and client-facing banking experience at **RBC and TD**.

I moved into analytics because I enjoy the part between *“we have data”* and *“so what should we do?”* Most of my projects start with a business question and then work through the data, modelling, validation, and interpretation needed to answer it.

📍 Toronto · 📊 Business & Data Analytics · 🐶 Usually working with my Chihuahua, Amiu, nearby

---

## Selected analytics projects

### 🏙️ Toronto Airbnb Pricing Analytics
**15,332 listings · DuckDB · Python · Tableau · Streamlit**

I wanted to know how much location matters for nightly price once you account for the listing itself. I used DuckDB to clean the raw listings, check the sample, and compare median prices by neighbourhood and room type. I then fitted a log-price regression in Python to compare listings with similar characteristics.

Holding the other model inputs constant, entire homes were priced **43.8% higher** than private rooms, while each additional kilometre from Union Station was associated with a **2.7% lower** nightly price. The Tableau dashboard shows the market comparisons, and the Streamlit app lets you change listing details to explore the model estimate.

[Explore the SQL queries](https://github.com/lambert-tan/toronto-airbnb-pricing-analytics#sql-layer-duckdb) · [View the project](https://github.com/lambert-tan/toronto-airbnb-pricing-analytics) · [Open Tableau dashboard](https://public.tableau.com/views/Toronto_Airbnb_Pricing_Analytics/Dashboard01MarketPulse) · [Try the pricing app](https://toronto-airbnb-pricing-analytics-jthhn2unchpj3ewyfbnyfq.streamlit.app/)

### 🛒 Negative Review Prediction in E-Commerce
**95,824 delivered orders · DuckDB · LightGBM · CatBoost**

How early can a service team spot an order likely to receive a one- or two-star review? I used SQL to build one record per order, aggregating items and payments before joining them so that larger baskets wouldn’t count more than once. I then compared two models using only the information available when an order was placed or delivered.

The placement model gives the team an earlier signal. At delivery, the additional fulfillment data improved test ROC-AUC from **0.658 to 0.775**. The highest-risk 10% of orders accounted for **43.6% of negative reviews** in the test set, a practical starting point for a team with limited follow-up capacity.

[Explore the SQL queries](https://github.com/lambert-tan/olist-negative-review-prediction#sql-pipeline-duckdb) · [View the project](https://github.com/lambert-tan/olist-negative-review-prediction)

### ❄️ Toronto Warming Centre Optimization
**7 centres · Python · Monte Carlo simulation · Integer optimization**

Would more staff or more beds help Toronto’s warming centres admit more people on a cold night? I used integer optimization to allocate staff under a **$33,000 nightly budget**, then stress-tested the plan across **5,000 simulated nights**.

The plan assigns 19 staff, enough to support 380 clients across a network with 301 beds. In the extreme-demand scenario, the centres admitted **297 of 306 people** and stayed within budget. That led me to compare where ten additional beds would help most. The model favoured placing five at Elizabeth and five at Scarborough.

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
