# Executive-B2B-Sales-Pipeline-Revenue-Analysis
## Project Overview
The objective of this project is to build an interactive executive dashboard to analyze B2B sales pipeline efficiency, identify bottlenecks across deal stages, evaluate sales agent performance, and assess revenue distribution across market sectors.

**[View Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/.17026898/viz/ExecutiveSalesPipelineDashboard/Dashboard1)**

## Tools & Technologies
* **Google BigQuery / SQL:** Data extraction, joining relational tables, and primary filtering.
* **Python (Pandas, Google Cloud BigQuery API):** DWH connection, feature engineering (calculating sales cycle length), handling missing values, and data export.
* **Tableau:** Building an interactive Executive Dashboard with KPIs, funnel analysis, and performance breakdowns.

## Dashboard Visualization

![Executive B2B Sales Pipeline Dashboard](Dashboard.png)

## Key Performance Indicators (KPIs)

| Metric | Value |
| :--- | :---: |
| **Total Revenue** | **$10.01M** |
| **Win Rate** | **48%** |
| **Avg Deal Size** | **$2.36K** |
| **Avg Sales Cycle** | **51–52 days** |


## Sales Funnel Breakdown

* **Prospecting:** 500 initial contacts.
* **Engaging:** 1,589 active prospects receiving pitch decks or negotiations.
* **Won:** 4,238 successfully closed deals.
* **Lost:** 2,473 lost deals.

##  Key Business Insights & Recommendations

### 1. Funnel Bottlenecks & Conversion Rates
* **Insight:** Only **48%** of deals that reach the final stage are won, meaning every second active negotiation ends in rejection.
* **Recommendation:** Shift operational focus toward optimizing conversion rates at the **Engaging** stage. Increasing the Win Rate by even **5%** will deliver a substantial surge in overall revenue.

### 2. Sector Revenue Analysis
* **Insight:** The **Retail** sector leads total revenue generation (**$1.87M**), followed by **Technology** and **Medical**. Conversely, **Services** and **Employment** contribute the least.
* **Recommendation:** Analyze whether low revenue in underperforming sectors is driven by lead shortage or high rejection rates. Scale successful sales playbooks from *Retail* and *Technology* across underperforming verticals.

### 3. Sales Agent Performance
* **Insight:** Top performer **Darcel Schlecht** significantly outperforms peers with **$1.15M** in closed revenue, driving nearly 25% of total sales among the top 10 agents.
* **Recommendation:** Reward high performance, analyze Darcel's target sector distribution, and package their closing techniques into internal training programs for the wider sales team.
