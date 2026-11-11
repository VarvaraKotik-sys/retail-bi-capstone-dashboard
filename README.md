# Retail Sales Performance Dashboard — BI Capstone, Part 3

Interactive dashboard built for the NPower BI Capstone Project (Part 3), based on the
curated BigQuery star schema from Part 2 (fact_sales; dim_customers, dim_products,
dim_stores, dim_date) and the Kaggle retail sales dataset (5,000 transactions,
10 Sep 2023 – 9 Sep 2025).

Open `index.html` in a browser — the file is fully self-contained (data embedded).

Pages: 1) Sales Overview, 2) Customer Insights, 3) Product & Store Performance.
Features: slicers (date, store, category, gender), drillthrough Store → Product →
Transaction, rich tooltips, conditional formatting on profit margins.

Key totals: Revenue 14,301,903.15 · Profit 4,999,583.24 · AOV 2,860.38 · Margin 35.0%.
