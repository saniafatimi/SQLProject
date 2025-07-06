# sales-cumulative-mtd-qtd-ytd-data-analysis-sql
data training project 

# SQL Cumulative Sales Analysis (MTD, QTD, YTD)

This project demonstrates how to analyze time-based data using SQL to generate:
- Month-To-Date (MTD)
- Quarter-To-Date (QTD)
- Year-To-Date (YTD)

🔸 The data includes 36 months of sample sales from 2022 to 2024.

🔸 The query uses `SUM() OVER(PARTITION BY ... ORDER BY ...)` to compute cumulative metrics.

Useful for:
- Financial analysis
- Sales tracking
- Power BI/Excel dashboards
