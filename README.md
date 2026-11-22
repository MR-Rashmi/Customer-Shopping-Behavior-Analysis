# Customer Shopping Behavior Analysis

## Project Overview

This project analyzes customer shopping behavior to understand
purchasing patterns, customer preferences, spending, discounts, and
factors that can support better business decisions.

The analysis uses **SQL, Python, and Power BI**. SQL is used to query
the customer dataset, Python is used for data preparation and
exploratory analysis, and Power BI is used to present the findings in an
interactive dashboard.

## Project Objectives

-   Analyze customer purchasing and spending patterns.
-   Compare revenue and purchasing behavior across customer groups.
-   Understand product-category and product preferences.
-   Examine discount usage and subscription status.
-   Explore customer purchase history and purchasing frequency.
-   Present key performance indicators and analysis in a dashboard.

## Tools and Technologies

-   PostgreSQL
-   SQL
-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Jupyter Notebook
-   Power BI

## Dataset

The project uses `customer_shopping_behavior.csv`.

-   Original dataset: **3,900 records and 18 columns**.
-   The cleaned dataset stored in PostgreSQL contains **3,900 records
    and 19 columns**.
-   Additional analysis fields include `age_group` and
    `purchase_frequency_days`.

The dataset includes customer demographics, purchased items, product
categories, purchase amounts, location, season, review ratings,
subscription status, shipping type, discount usage, previous purchases,
payment method, and purchase frequency.

## Project Workflow

1.  **Data loading:** Load the CSV dataset for analysis.
2.  **Data cleaning:** Check data types, missing values, duplicates, and
    data consistency; prepare the data for analysis.
3.  **Feature engineering:** Create additional fields such as age group
    and purchase-frequency days.
4.  **SQL analysis:** Use PostgreSQL to answer business questions and
    calculate customer and sales metrics.
5.  **Python analysis:** Perform exploratory data analysis and create
    visualizations.
6.  **Dashboard:** Use Power BI to present key metrics and trends.
7.  **Insights:** Summarize findings and develop business
    recommendations based on the analysis.
