# Supermarket Sales Performance Dashboard | Power BI

Interactive supermarket sales analytics built in **Microsoft Power BI**, using the [Supermarket dataset on Kaggle](https://www.kaggle.com/datasets/datascikhan/supermarket). The dashboard analyzes sales activity across **2023–2024**, with views of overall performance, product and department results, and quarterly sales trends.

## Problem Statement

Supermarket transaction data covers many products, departments, and time periods. Examining these records individually makes it difficult to identify the main sources of revenue, understand sales volume and margin contribution, and track changes in performance over time.

This project brings those measures together in an interactive dashboard to support clearer comparisons and data-driven business analysis.

## Approach

Developed a **three-page Power BI dashboard** covering the process from data modeling and DAX calculations to interactive visualization.

- Built measures for **Gross Sales, Total Margin, Margin %, Quantity Sold, Unique Customers, Unique Products Sold,** and **Average Transaction Value**.
- Organized sales data by product, category, subcategory, department, month, year, and quarter.
- Used date-based calculations for **Previous Quarter Sales, Sales Difference,** and **QoQ Growth %**.
- Added date and department filters, product-ranking charts, drillable tables, and conditional colors for positive and negative quarterly growth.

## Outcome

Created a consolidated view of supermarket performance that makes it easier to compare revenue and sales volume across departments, identify high-performing product subcategories, review margin contribution, and spot quarterly growth or decline.

## Dashboard Pages

### 1. Sales Overview

Provides an overall view of key sales indicators, a monthly gross-sales comparison for 2023 and 2024, a department revenue ranking, and a detailed breakdown by department and category.

<img width="987" height="554" alt="Screenshot 2026-10-28 232018" src="https://github.com/user-attachments/assets/10470aac-2ebe-4e55-b0cc-8e8cb1e811f3" />

### 2. Product & Department Performance

Examines **quantity sold by department**, **Top 10 Product Subcategories by Gross Sales**, and **margin contribution by department**, alongside product-level sales and margin details.

<img width="987" height="555" alt="Screenshot 2026-10-28 232034" src="https://github.com/user-attachments/assets/e5ffa3ed-4811-4097-bef4-56b08a96ca81" />

### 3. Sales Trend & Quarterly Comparison

Compares quarterly revenue across 2023 and 2024, tracks monthly sales patterns, and highlights positive and negative **QoQ Growth %**. KPI cards compare the latest selected quarter with the previous quarter.

<img width="918" height="517" alt="Screenshot 2026-10-28 232055" src="https://github.com/user-attachments/assets/fbaa68d5-6ed8-4721-8818-3a130eb1dd10" />

## Key Findings

- **Food** is the leading department, generating approximately **4.62M in gross sales**, **411K units sold**, and **16.08K in total margin**.
- The highest-revenue product subcategories shown are **Trash Bags (~80K)**, **T-Shirts (~79K)**, and **Yogurt (~75K)**.
- Quarterly growth reached **+2.01% in Q3 2023**, while **Q3 2024 declined by 1.45%** compared with the preceding quarter.
- **Q4 2024 recovered by 0.73%**, representing a sales increase of approximately **10.73K** compared with Q3 2024.

## Data Source

[Kaggle - Supermarket Dataset(datascikhan/supermarket)](https://www.kaggle.com/datasets/datascikhan/supermarket)
