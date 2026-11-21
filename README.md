# Hi, I’m Lambert 👋

### I like turning messy data into answers people can actually use.

I’m studying for a Master of Management in Analytics at Queen’s University. Before grad school, I studied statistics and worked with banking clients at RBC and TD. What drew me to analytics was the part between “we have data” and “so what should we do?”

📍 Toronto · 🐶 Usually working with my dog, Amiu, nearby

## 🧰 Skills in practice

| Skill | How I use it | Work sample |
|---|---|---|
| SQL and data quality | Aggregate items and payments before joining them to orders, so a basket with three items still counts as one customer outcome. | [DuckDB order pipeline](https://github.com/lambert-tan/olist-negative-review-prediction/blob/main/sql/01_build_master_orders.sql) |
| Customer segmentation and model validation | Use Python to identify order patterns, then evaluate how well risk scores concentrate negative reviews within a service team’s review capacity. | [Clustering notebook](https://github.com/lambert-tan/olist-negative-review-prediction/blob/main/notebooks/02_clustering.ipynb) · [Score validation](https://github.com/lambert-tan/olist-negative-review-prediction/blob/main/docs/model_validation_report.md) |
| Statistical modelling and communication | Estimate how listing characteristics relate to asking price, build a Tableau view for exploring comparable properties, and explain the estimates in a short memo for hosts. | [Tableau dashboard](https://public.tableau.com/views/Toronto_Airbnb_Pricing_Analytics/Dashboard01MarketPulse) · [Pricing memo](https://github.com/lambert-tan/toronto-airbnb-pricing-analytics/blob/main/reports/business_memo.md) |
| Operational planning | Simulate the same nights under two transfer policies to isolate the effect of bed availability on unmet demand. | [Python sensitivity analysis](https://github.com/lambert-tan/toronto-warming-centre-optimization/blob/main/notebooks/warming_centre_end_to_end.ipynb) |

## 📂 Selected projects

### 🛒 Prioritizing customer follow-up at Olist

If a service team can review one in ten orders, when should it choose them? I built an order-level dataset from eight source tables and compared two rankings on the same held-out orders. At placement, the highest-risk 1,917 orders included **567** that received a one- or two-star review. At delivery, the same number of review slots identified **1,071**. Waiting gives the team a better-targeted list, but less time to resolve a problem before the customer experiences it.

[Project and results](https://github.com/lambert-tan/olist-negative-review-prediction) · [SQL pipeline](https://github.com/lambert-tan/olist-negative-review-prediction#sql-pipeline-duckdb) · [Validation report](https://github.com/lambert-tan/olist-negative-review-prediction/blob/main/docs/model_validation_report.md)

### 🏙️ Benchmarking Toronto Airbnb asking prices

For a host choosing a nightly rate, the first decision is which listings belong in the comparison. I led the original graduate project and rebuilt the analysis and pricing app for this portfolio. Across 15,332 listings, entire homes had a median asking price of CAD 167, compared with CAD 65 for private rooms. In the regression, the estimated difference was **43.8%** at comparable capacity, location and other measured characteristics. I’d use the dashboard to find comparable properties before using the model to explore a rate.

[Project and SQL](https://github.com/lambert-tan/toronto-airbnb-pricing-analytics#sql-layer-duckdb) · [Tableau dashboard](https://public.tableau.com/views/Toronto_Airbnb_Pricing_Analytics/Dashboard01MarketPulse) · [Pricing app](https://toronto-airbnb-pricing-analytics-jthhn2unchpj3ewyfbnyfq.streamlit.app/)

### ❄️ Stress-testing Toronto warming centre capacity

Our graduate team developed a staffing plan for seven warming centres. I rebuilt the demand simulation in Python to see where that plan could fall short. In the original extreme-weather scenario, nine people were turned away. Across 574 simulated extreme nights, the average was **17 per night**. I also tested what happens when two extreme-weather sites cannot receive transfers on moderate nights. With the same arrivals and staff, unmet demand appeared on **29.7% of moderate nights**. Before requesting more beds, I’d ask operators which sites can actually receive a referral on each shift.

[Project and scenario results](https://github.com/lambert-tan/toronto-warming-centre-optimization) · [Simulation notebook](https://github.com/lambert-tan/toronto-warming-centre-optimization/blob/main/notebooks/warming_centre_end_to_end.ipynb)

![Physical beds and the number of clients staff can support at each of seven Toronto warming centres](https://raw.githubusercontent.com/lambert-tan/toronto-warming-centre-optimization/main/assets/capacity_by_centre.svg)

I also use Excel in my banking and portfolio analysis work.

[LinkedIn](https://www.linkedin.com/in/lamberttan/) · [Email](mailto:tanjianglin845@gmail.com)
