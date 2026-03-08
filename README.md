# Djafar Mbae Mmadi — Analytics Engineer

I turn raw data into decisions.
From pipeline architecture to the final visual a manager acts on — I own the full chain.

3 years of experience as a freelance analytics engineer.

Based in Dakar, Senegal · Available remotely for French-speaking Europe, French-speaking Africa and the United States · French and English

---

## What I do

I design and build end-to-end data pipelines structured around the Medallion architecture
(Bronze / Silver / Gold), powered by dbt, PostgreSQL and Python. I close the loop with
Power BI reporting layers that include production-grade DAX measures, row-level security,
and semantic models built for real business users.

What sets my work apart is the analytical depth behind it — I validate features statistically
before modeling, I test my pipelines, and I document everything a team would need to maintain
or extend what I build.

---

## Featured Projects

### [Healthcare Readmission Pipeline](https://github.com/23dede/healthcare-readmission-pipeline)
End-to-end prediction pipeline for 30-day hospital readmission risk.

Full Medallion pipeline with dbt Core, 3 Python notebooks covering EDA, statistical validation
and logistic regression, 56 DAX measures across 7 folders, and 4 RLS roles for hospital staff
profiles. Statistical validation includes Mann-Whitney U, chi-square, VIF multicollinearity check
and stratified 5-fold cross-validation with bootstrap confidence intervals.
Data is entirely synthetic, generated with the Python Faker library.

`Python` `dbt Core` `PostgreSQL` `scikit-learn` `Power BI` `DAX` `RLS`

---

### [Banking Intelligence Platform](https://github.com/23dede/powerbi-banking-dashboard)
Credit risk, fraud detection and portfolio performance dashboard.

Synthetic banking data generated with Faker across 5 tables, full Medallion pipeline,
3 Power BI report pages, 16 DAX measures, and 3 RLS roles scoped by business function.
Data is entirely synthetic, generated with the Python Faker library.

`Python` `Faker` `PostgreSQL` `Power BI` `DAX` `RLS`

---

### [Olist Medallion Architecture](https://github.com/23dede/olist-medallion-architecture)
E-commerce analytics pipeline on 1.55 million rows of real Olist data.

Bronze to Silver to Gold pipeline with full type casting and data cleaning, a DimDate
semantic layer, and a DAX measure that encodes partial-month exclusion logic to prevent
misleading trend artifacts in the time series.
Data sourced from the public Olist Brazilian E-Commerce dataset on Kaggle.

`SQL` `PostgreSQL` `Power BI` `DAX`

---

## Technical Stack

| Layer | Tools |
|-------|-------|
| Transformation | dbt Core, SQL, Python 3.11 |
| Storage | PostgreSQL 15 |
| Analysis and Modeling | pandas, scikit-learn, scipy, statsmodels |
| Business Intelligence | Power BI Desktop, DAX, RLS |
| Data Generation | Faker |
| Version Control | Git, GitHub |

---

## Currently

Building a freelance portfolio targeting analytics engineering and BI consulting missions
in French-speaking Europe, French-speaking Africa and the United States. Open to remote
project engagements, data transformation mandates, and Power BI consulting contracts.

Reach me via GitHub or connect on LinkedIn.
