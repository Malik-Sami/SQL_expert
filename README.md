# Five Days of SQL

A five-day, hands-on journey through SQL: starting with querying and data exploration, then progressing through joins, analytical query patterns, and reusable business intelligence pipelines. The work uses PostgreSQL and real-world-style datasets to build practical skills from the fundamentals toward advanced SQL analytics.

## Learning roadmap

| Day | Focus | What you will practice |
| --- | --- | --- |
| [Day 1](./Day1/README.md) | SQL foundations with Superstore sales | Creating a table, importing a CSV, retrieving and filtering data, and performing basic aggregations. |
| [Day 2](./Day2/README.md) | Relationships and joins with DVD Rental | Discovering a relational schema and joining tables to answer questions about customers, films, rentals, and revenue. |
| [Day 3](./Day3/README.md) | Analytical SQL with DVD Rental | Aggregations, `HAVING`, subqueries, CTEs, and window functions for rankings, latest records, and period-over-period analysis. |
| [Day 4](./Day4/README.md) | Music Store business intelligence | Building customer profiles, segmentation, recommendations, country rankings, and a consolidated executive reporting pipeline. |
| [Day 5](./Day5/enterprise_analytics_hackathon/README.md) | AdventureWorks analytics hackathon | Designing a layered PostgreSQL analytics pipeline with dimensions, facts, reusable metrics, and dashboard-ready KPI datasets. |

The daily folders contain the exercises, SQL scripts, datasets, diagrams, screenshots, and notes for each stage. Check the README in a day’s folder for its specific materials and setup instructions.

## Skills covered

- Creating tables and loading data into PostgreSQL
- Selecting, filtering, sorting, and aggregating records
- Understanding relational schemas and joining related tables
- Using subqueries and CTEs to organize multi-step analysis
- Applying window functions such as `ROW_NUMBER()`, `RANK()`, `DENSE_RANK()`, and `LAG()`
- Building customer, product, employee, and regional metrics
- Translating query results into business insights and recommendations
- Structuring reusable analytics datasets for reporting and dashboards

## Getting started

1. Use PostgreSQL and a SQL client such as pgAdmin 4.
2. Start with [Day 1](./Day1/README.md) and work through the folders in order.
3. Follow each day’s README for dataset setup, database names, and any project-specific instructions.
4. Run the SQL scripts against the corresponding database and sample data described for that day.

The projects use different datasets and database schemas, so there is no single setup command for the entire folder. Some datasets are provided locally; others may need to be downloaded as described in the relevant day’s documentation.

## Capstone

The final-day AdventureWorks submission goes beyond standalone queries: its analytical views are organized into four layers, from core dimensions and facts through intermediate metrics to executive KPI datasets. See the [Day 5 hackathon README](./Day5/enterprise_analytics_hackathon/README.md) for its architecture, design decisions, and assumptions.
