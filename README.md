# Hi, I’m Lambert

I’m a Toronto-based analyst with a background in statistics and client-facing banking at RBC and TD. I’m completing the Master of Management in Analytics at Smith School of Business, Queen’s University.

## Prioritizing customer follow-up at Olist

If a service team can review one in ten orders, when should it choose them? I built an order-level dataset from eight source tables and compared two rankings on the same held-out orders. At placement, the highest-risk 1,917 orders included **567** that received a one- or two-star review. At delivery, the same number of review slots identified **1,071**. Waiting gives the team a better-targeted list, but less time to resolve a problem before the customer experiences it.

[Project and results](https://github.com/lambert-tan/olist-negative-review-prediction) · [SQL pipeline](https://github.com/lambert-tan/olist-negative-review-prediction#sql-pipeline-duckdb) · [Validation report](https://github.com/lambert-tan/olist-negative-review-prediction/blob/main/docs/model_validation_report.md)

## Benchmarking Toronto Airbnb asking prices

For a host choosing a nightly rate, the first decision is which listings belong in the comparison. I led the original graduate project and rebuilt the analysis and pricing app for this portfolio. Across 15,332 listings, entire homes had a median asking price of CAD 167, compared with CAD 65 for private rooms. In the regression, the estimated difference was **43.8%** at comparable capacity, location and other measured characteristics. I’d use the dashboard to find comparable properties before using the model to explore a rate.

[Project and SQL](https://github.com/lambert-tan/toronto-airbnb-pricing-analytics#sql-layer-duckdb) · [Tableau dashboard](https://public.tableau.com/views/Toronto_Airbnb_Pricing_Analytics/Dashboard01MarketPulse) · [Pricing app](https://toronto-airbnb-pricing-analytics-jthhn2unchpj3ewyfbnyfq.streamlit.app/)

## Stress-testing Toronto warming centre capacity

Our graduate team developed a staffing plan for seven warming centres. I rebuilt the demand simulation in Python to see where that plan could fall short. In the original extreme-weather scenario, nine people were turned away. Across 574 simulated extreme nights, the average was **17 per night**. The model also assumes spare beds can receive transfers across sites. Which centres can actually accept transfers is a question I’d settle with operators before using the simulation to plan a shift.

[Project and scenario results](https://github.com/lambert-tan/toronto-warming-centre-optimization) · [Simulation notebook](https://github.com/lambert-tan/toronto-warming-centre-optimization/blob/main/notebooks/warming_centre_end_to_end.ipynb)

I work with SQL, Python, Tableau and Excel. Outside work, I’m usually exploring Toronto or spending time with my Chihuahua, Amiu.

[LinkedIn](https://www.linkedin.com/in/lamberttan/) · [Email](mailto:tanjianglin845@gmail.com)
