# Apple Products Pricing & Sales Analysis

> Retail Analytics | SQL | Data Cleaning | Business Intelligence

A retail analytics project focused on Apple product pricing, discount strategy, profitability, and sales performance across e-commerce platforms from 2020 to 2026.

This project demonstrates end-to-end data analysis capabilities in a realistic business context. It covers raw data preparation, SQL-based transformation, exploratory analysis, and dashboard storytelling to answer pricing and sales questions that matter to retail and commercial decision-makers.

## Professional Summary

I build data-driven solutions that turn raw business data into clear, actionable insights. This project reflects my ability to clean and structure datasets, analyze pricing and performance trends using SQL, and present findings through dashboards in a way that supports commercial decision-making.

## Business Objective

The goal of this project is to understand how Apple products perform across discount cycles, product conditions, and sales events while identifying patterns that influence profitability and customer engagement.

The analysis helps answer practical business questions such as:

- How do discount levels impact profit margins?
- Which product categories generate the strongest value and revenue outcomes?
- Do sale events improve product visibility and review activity?
- How does product condition influence customer perception and pricing?
- What year-over-year trends can inform pricing and campaign strategy?

## Why This Project Matters

Pricing and sales decisions in retail are driven by a combination of margin, demand, customer behavior, and promotional timing. This project reflects the kind of analytical problem solving used in data and BI roles, where business questions must be converted into structured data decisions and actionable insights.

It is designed to show that I can work with imperfect raw datasets, build a clean analytical workflow, and turn findings into meaningful business recommendations.

## Role Relevance

This project is highly relevant for:

- Data Analyst
- Business Analyst
- BI Analyst
- Retail Analytics Analyst
- Commercial / Pricing Analyst

It showcases the ability to:

- clean and transform raw data
- write SQL for analysis and aggregation
- interpret business performance trends
- communicate findings through dashboards and reporting

## Tools and Technologies

- PostgreSQL for ETL and SQL analysis
- pgAdmin for database management
- CSV-based data ingestion
- Excel for supporting analysis and dashboard preparation
- Power BI for business visualization
- GitHub for portfolio presentation and project documentation

## Dataset Overview

The dataset contains product-level transaction and pricing data with fields including:

- Date and year
- Platform information
- Product category and model name
- Product condition
- Launch and current prices in USD and INR
- Profit and profit percentage
- Discount percentage
- Sale event type
- Rating and review count
- Stock status

## Data Cleaning and Transformation

Before analysis, the raw data was processed to ensure data quality and consistency. The workflow included:

- creating a staging table for raw intake
- standardizing text-based and numeric fields
- converting pricing and percentage values into appropriate formats
- normalizing date and currency representations
- cleaning review and rating fields for reliable analysis
- loading cleaned data into a final analytics-ready table

## SQL Analysis Workflow

The repository includes SQL scripts designed to support a complete analytical pipeline:

- schema creation and table definitions
- data import and transformation
- conversion of raw fields into usable business metrics
- aggregation and trend analysis by year, category, and model
- discount and event-based sales analysis
- reporting logic for business insights

Key SQL files:

- create_table.sql
- import_and_alter.sql
- analysis_query.sql
- project_of_sql.sql

## Key Questions Explored

The analysis focuses on core commercial questions, including:

- Which products contributed the most profit?
- What is the average profit trend across categories and models?
- Which sales events generated the strongest discount behavior?
- How does discount depth relate to review volume and engagement?
- What are the year-over-year sales and pricing trends?
- How do product conditions affect value perception and satisfaction?

## Key Insights

The project highlights practical business patterns, including:

- discount-led promotions influence customer response and engagement
- profit margins are sensitive to discount intensity
- sale events create meaningful shifts in pricing and demand patterns
- value perception remains important even when product prices are reduced
- product categories and models show different levels of performance over time

## Dashboard and Storytelling

The visual outputs in the project help translate raw analysis into business-ready insights.

![Excel Dashboard](image/excel_dashboard.JPG)

![Power BI Dashboard](image/power_bi_dashboard.JPG)

These dashboards are useful for presenting findings to non-technical stakeholders and making pricing strategies easier to interpret.

## Project Structure

```text
Git Project/
├── README.md
├── data/
│   └── raw_data.csv
├── dashboard/
│   ├── apple_products_pricing_2020_2026.xlsx
│   └── project_git.pbix
├── image/
│   ├── excel_dashboard.JPG
│   └── power_bi_dashboard.JPG
├── scripts/
│   ├── analysis_query.sql
│   ├── create_table.sql
│   ├── import_and_alter.sql
│   └── project_of_sql.sql
```

## How to Run This Project

1. Create the database in PostgreSQL.
2. Execute the schema setup script from scripts/create_table.sql.
3. Import the raw CSV into the staging table.
4. Run the transformation logic from scripts/import_and_alter.sql.
5. Execute the analysis queries from scripts/analysis_query.sql.
6. Open the Excel or Power BI dashboard to review the final outputs.

## Business Recommendations

This project supports recommendations such as:

- optimizing discount depth to preserve profitability
- identifying categories that are strongest for margin and sales performance
- planning sale campaigns around periods of higher conversion potential
- improving pricing decisions using historical trend analysis
- using dashboards to support ongoing commercial monitoring

## Skills Demonstrated

- Data extraction and ingestion
- Data cleaning and transformation
- SQL querying and data aggregation
- Retail and pricing analysis
- KPI and trend interpretation
- Dashboard design and executive reporting
- Business problem framing and insight generation

## About Me

I am a data-focused professional passionate about transforming business questions into analytical solutions. My interests lie in SQL, data cleaning, KPI analysis, business intelligence, and using data to support smarter decisions across retail and commercial environments.

I enjoy building projects that combine technical rigor with business storytelling, making complex data understandable and useful for decision-makers.

## Author

Lalit Kumar

Data Analyst | BI Enthusiast

LinkedIn: https://www.linkedin.com/in/lalit-kumar-d05-ds/
Email: lkk11002003@gmail.com
