# 📊 Revenue & Retention Analysis
## Product & Business Data Analytics Project

## 🧠 Problem Statement
Understanding revenue growth alone is insufficient without understanding customer retention and long-term value.
This project analyzes revenue trends, customer retention behavior, and cohort-based customer value to inform product and growth decisions.

## 🛠️ Tools & Technologies
* Python (Pandas, NumPy, Matplotlib) – cleaning, EDA, cohort analysis
* SQL – revenue and customer metrics
* Git/GitHub – version control and documentation

## 📈 Dataset
* Online Retail transcation dataset (UCI Machine Learning Repository)
* ~400K cleaned transactions
* Each row represents a product-level purchase

## Key Revenue Insight
* Revenue shows seasonal patterns with strong early-period concentration.
* Revenue per customer increases over time among retained customers.
* Early customer engagement drives the majority of revenue.

## Retention & Cohort Insights
* Customer retention drops sharply after the first purchase.
* A smaller subset of cusomers remains active long-term
* Cohorts with stronger early retention generate higher long-term value

## Customers Value (CLV Thinking)
* Revenue is front-loaded in early months, whiles longterm value depends on rentions quality
* Retained customers become increasing valuable over time
* Cohort-based analysis reveals significant differences in customer lifetime value

## 🎯 Business Recommendations
* Improve onboarding and first-purchase experience to reduce early churn.
* Prioritize acquisition channels that produce high-retention cohorts.
* Focus retention efforts on customers showing early engagement signals.
* Evaluate marketing performance using cohort value, not just acquisition volume.


📁 Project Structure
````
revenue-retention-analysis/
│
├── data/
│   ├── raw/
│   └── cleaned/
│       └── online_retail_cleaned.csv
│
├── notebooks/
│   ├── revenue_cleaning.ipynb
│   ├── revenue_eda.ipynb
│   ├── retention_cohort.ipynb
│   └── revenue_retention_value.ipynb
│
└── README.md
````

🚀 Outcome
This project demonstrates end-to-end Product Data Analytics capability, combining revenue analysis, customer retention, and cohort-based value insights to support data-driven decision-making.
