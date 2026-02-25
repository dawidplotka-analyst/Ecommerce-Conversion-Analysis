# 📊 Global E-commerce Performance Analysis
### Project Goal
An end-to-end analysis of revenue trends and user conversion funnel for a global e-commerce platform using SQL (BigQuery), Python, and Tableau.

### Key Technical Steps:
* SQL (BigQuery): Integrated 6 different tables (sessions, params, accounts, orders, products) using multi-level LEFT JOINs to build a comprehensive data foundation.

* Data Modeling: Applied CTEs for clean code structure and UNION ALL to create a vertical event-based model, optimized for funnel analysis.

* Python (Pandas): Automated data extraction via google.cloud.bigquery and performed data validation using describe() and info() methods.

* Business Logic: Standardized raw technical fields into clear business dimensions like is_verified_account or traffic_channel for end-user reporting.

### Top Business Insights
* High Potential: Identified Taiwan as a leader in registration efficiency (8.5%).

* Optimization Gap: France shows high traffic but lower-than-average conversion (7.6%), signaling a need for sign-up process UX improvements.

* Retention: Data suggests a drop-off in user activity after 4 weeks; recommended personalized re-engagement campaigns.

### Tools Used
SQL | Python (Pandas/Matplotlib) | Tableau | Google BigQuery
