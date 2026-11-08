<p align="center"><a href="https://github.com/Raul9915/Raul9915/blob/main/README.es.md">🇪🇸 Versión en español</a></p>

<h1 align="center">Raul Mendoza Sotomayor</h1>

<p align="center">
  <strong>Data Analyst | Business Intelligence | Python | SQL | Power BI</strong>
</p>

<p align="center">
  Industrial Engineer with a Master's in Data Analytics (TECNUN – University of Navarra).<br/>
  I turn messy operational data into automated pipelines, reliable KPIs and dashboards that drive business decisions.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/raul-mendoza-sotomayor"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:raulmen_sot99@hotmail.com"><img src="https://img.shields.io/badge/Email-555555?style=flat&logo=microsoftoutlook&logoColor=white" alt="Email"/></a>
  <a href="https://doi.org/10.14445/22315381/IJETT-V72I11P118"><img src="https://img.shields.io/badge/Publication-IJETT_2024-1f6feb?style=flat&logo=bookstack&logoColor=white" alt="Publication"/></a>
</p>

<p align="center">📍 Lima, Peru · Open to remote roles · Spanish (native) · English (advanced)</p>

---

### Business Understanding + Advanced Analytics + Automation

I work where business questions meet data engineering: I find the problem, build the pipeline, define the KPIs and deliver a dashboard the team actually uses.

## About Me

- **Data Strategy Analyst – Collections at Divemotor (Peru):** built the team's first two receivables portfolio dashboards (after-sales and commercial vehicles), including the data model, DAX measures and load processes, and replaced manual Excel tracking of delinquency, debt aging and recovery with automated reporting.
- **Data engineering:** ETL pipelines in Python and SQL integrating SAP, CRM and other corporate sources, organized in a **Medallion architecture (Bronze → Silver → Gold)** on Parquet with built-in data quality checks.
- **AI & automation:** data cleaning, deduplication and normalization pipelines for Salesforce CRM at the University of Navarra; hands-on work with Azure OpenAI and AI agents for business use cases.
- **Industrial engineering mindset:** process optimization, Lean and continuous improvement applied to data workflows.

## Tech Stack

| Area | Tools |
|---|---|
| **Programming & Analytics** | Python (pandas, NumPy, matplotlib, seaborn), SQL, R, Jupyter, Advanced Excel |
| **Business Intelligence** | Power BI, DAX, Power Query, Google Data Studio, data modeling, KPI design |
| **Data Engineering** | ETL/ELT, Medallion architecture, Parquet, DuckDB, data validation, Power Automate |
| **Machine Learning & AI** | scikit-learn (classification, regression, Random Forest, gradient boosting, probability calibration), time series forecasting, NLP, Azure OpenAI |
| **Cloud & Enterprise Tools** | SAP, Salesforce CRM, Microsoft Azure, Microsoft Fabric, SharePoint, Git & GitHub |

## Professional Impact

*Real results from past roles, as reported on my résumé.*

| Result | Context |
|---|---|
| **~90% less** data processing time | University of Navarra · AI & Data Science |
| **~80% fewer** manual processing errors | University of Navarra · AI & Data Science |
| **~15% shorter** delivery times and **~8% lower** costs | Gloria · Trade Marketing (process improvement initiatives) |
| **~20% fewer** SAP billing process errors | Abbott Laboratories · Supply Chain (project with IBM) |

## Featured Projects

### ⭐ Accounts Receivable Analytics & ETL Pipeline

<a href="https://github.com/Raul9915/accounts-receivable-analytics-pipeline"><img src="https://raw.githubusercontent.com/Raul9915/accounts-receivable-analytics-pipeline/main/images/powerbi_overview.png" alt="Power BI dashboard - Accounts Receivable portfolio" width="100%"/></a>

Medallion pipeline (Bronze → Silver → Gold) that turns monthly SAP-style receivables exports into a trusted portfolio history, served from **SQL Server** to a **Power BI** dashboard.
`Python` `DuckDB` `Parquet` `SQL Server (T-SQL)` `Power BI / DAX` `pytest` · **[View repository →](https://github.com/Raul9915/accounts-receivable-analytics-pipeline)**

- 11 data-quality rules, rejected-records log and reconciliation checks between every layer
- Star schema with PK/FK constraints, reporting views and semi-additive DAX measures
- Insight: the portfolio grew 14% but overdue debt almost doubled; 26% of customers hold 80% of the overdue balance *(synthetic data)*

### ⭐ Credit Risk & Delinquency Analytics

<a href="https://github.com/Raul9915/credit-risk-delinquency-analytics"><img src="https://raw.githubusercontent.com/Raul9915/credit-risk-delinquency-analytics/main/images/05_strategy_drivers.png" alt="Data Studio report - approval strategy and PD model drivers" width="100%"/></a>

Credit-risk analytics on the public Home Credit dataset (307K applicants, 58M raw records): a DuckDB Medallion pipeline, delinquency roll rates, vintage cohorts and a calibrated probability-of-default (PD) model, reported in **Google Data Studio**.
`Python` `DuckDB` `SQL` `scikit-learn` `Google Data Studio` `pytest` `GitHub Actions` · **[View repository →](https://github.com/Raul9915/credit-risk-delinquency-analytics)** · **[Live report →](https://datastudio.google.com/reporting/10911058-bc14-4835-a65a-9f6e37476f98)**

- Monthly delinquency transition matrices and Kaplan-Meier vintage curves (default = 90+ days past due)
- Calibrated gradient-boosting PD model: ROC-AUC 0.774, Gini 0.548 on a held-out test set; risk bands A–E range from 1.4% to 22.0% default rate
- Insight: approving the 80% lowest-risk applicants lowers the approved book's default rate from 8.07% to 4.60% *(simulated policy on the held-out test set, public data)*

### Roadmap

> Each project is a complete business case (problem → data → method → dashboard → recommendations) built with **public or synthetic data only**.

| Project | Business question | Stack | Status |
|---|---|---|---|
| **[Accounts Receivable Analytics & ETL Pipeline](https://github.com/Raul9915/accounts-receivable-analytics-pipeline)** | How do we turn raw SAP receivables files into a trusted, historical portfolio view? | Python, DuckDB, Parquet, SQL Server, Power BI | ✅ Published |
| **[Credit Risk & Delinquency Analytics](https://github.com/Raul9915/credit-risk-delinquency-analytics)** | Which customers are likely to roll into deeper delinquency, and where should the approval cut-off be? | Python, DuckDB, SQL, scikit-learn, Data Studio | ✅ Published |
| **Sales & Business Intelligence Dashboard** | Where are revenue and margin being won or lost? | Power BI, DAX, Power Query | Planned |
| **Customer Segmentation with Machine Learning** | Which customer groups deserve different commercial strategies? | Python, K-Means, PCA | Planned |
| **Time Series Forecasting** | How much will we sell next quarter, and how confident are we? | Python, SARIMA, ML baselines | Planned |
| **CRM Data Automation & AI** | How do we keep CRM records clean, deduplicated and classified automatically? | Python, APIs, NLP | Planned |

## Education

- **Master's in Data Analytics in Engineering** — TECNUN, University of Navarra, Spain (2024–2025)
- **B.S. in Industrial Engineering** — University of Lima, Peru (2018–2022)

## Certifications

| Credential | Issuer | Year |
|---|---|---|
| Microsoft Certified: Azure AI Fundamentals | Microsoft | 2025 |
| Applied Skills: Build a Natural Language Processing Solution with Azure AI Language | Microsoft | 2025 |
| Certified ScrumMaster® (CSM®) | Scrum Alliance | 2025 |
| Applied Skills: Implement a Data Science and Machine Learning Solution with Microsoft Fabric | Microsoft | 2024 |
| Applied Skills: Develop Generative AI Solutions with Azure OpenAI Service | Microsoft | 2024 |

**Specialization Program in Data Science, Machine Learning & Artificial Intelligence** — Universidad Nacional Agraria La Molina, CECAP-FC (2026 · 180 academic hours · Power BI, supervised & unsupervised ML, deep learning, NLP)

**Selected training:** Python Applied to Data Science — PUCP (2024) · Applied Analytics for Executives — Pacífico Business School (2024) · Budgeting & Cash Flow Modeling in Excel — University of Lima (2024) · Big Data: Data-Driven Decisions — University of Navarra (2023) · SQL101x: Introduction to SQL and Relational Databases — UPValenciaX / edX · Data Analytics — IDAT (2022)

## Publication

**Optimizing Beverage Manufacturing: Integrating Lean Manufacturing and Machine Learning to Enhance Efficiency and Reduce Waste**
R. Mendoza Sotomayor (first author), J. A. Sabogal-Arias, J. C. Quiroz-Flores · *International Journal of Engineering Trends and Technology*, vol. 72, no. 11, pp. 155–174, 2024 · [DOI](https://doi.org/10.14445/22315381/IJETT-V72I11P118)

## Let's Connect

Hiring for **Data Analyst**, **BI Analyst** or **AI-enabled analytics** roles? I'd be glad to talk — reach me on [LinkedIn](https://www.linkedin.com/in/raul-mendoza-sotomayor) or at [raulmen_sot99@hotmail.com](mailto:raulmen_sot99@hotmail.com).
