# TechNova Gadgets: Discount Effectiveness Analysis

## Project Overview

Are the discounts offered by TechNova Gadgets helping the business generate profitable sales?

Discounts are commonly used to attract customers, increase sales, and remain competitive. However, while they may increase sales activity, they can also reduce profit margins and overall profitability.

This project analyses TechNova Gadgets' sales data to evaluate the relationship between discount levels, revenue, profit, and profit margins.

Using Microsoft Excel, I cleaned and transformed the dataset, performed data aggregation, developed PivotTables and interactive visualizations, and built an interactive dashboard to support business decision-making.

The objective was to understand how different discount levels relate to business performance and identify opportunities for improving discount strategies.

---

## Business Problem

TechNova Gadgets needs to understand whether its discount strategy supports profitable sales.

The analysis focuses on the following business questions:

1. How does revenue and profit vary across different discount levels?
2. What happens to profit margins as discount percentages increase?
3. Which product categories generate the highest profit margins?
4. Which product categories contribute the most to total profit?
5. What insights can management use to evaluate its discount strategy?

---

## Dataset Overview

The dataset used for this project is a synthetic sales dataset sourced online.

It contains transactional sales information covering different products, discount percentages, order statuses, sales channels, and geographical regions.

The dataset was used to simulate a realistic business environment in which sales performance and discount effectiveness could be evaluated.

### Dataset Components

The project contains the following data stages:

| Dataset | Description |
|---|---|
| Raw Dataset | Original synthetic dataset sourced online. |
| Transformed Dataset | Cleaned, aggregated, and transformed dataset prepared for analysis. |
| Completed Orders | Records filtered to include only completed transactions, forming the basis of the discount effectiveness analysis. |

---

## Project Workflow

The project followed a structured data analysis workflow, from sourcing the dataset to building the final dashboard.

### 1. Dataset Sourcing

The first step was sourcing a synthetic sales dataset online.

The dataset provided the transactional information required to investigate sales performance, product profitability, and discount effectiveness.

### 2. Data Cleaning

The raw dataset was imported into Microsoft Excel and reviewed for data quality.

Initial cleaning and preparation were carried out to make the dataset suitable for analysis.

### 3. Data Aggregation and Transformation

The dataset was further prepared through aggregation and transformation.

This involved organizing the available data fields and preparing the information required for subsequent analysis and visualization.

### 4. Order Status Analysis

One important step was examining the `Order_Status` column.

The dataset contained four distinct order statuses:

- Completed
- Pending
- Canceled
- Returned

For this particular analysis, I decided to use only completed transactions.

The reason was straightforward: transactions that were still pending, canceled, or returned should not form the basis of an analysis intended to evaluate the profitability of completed sales.

I therefore extracted all records with a `Completed` order status and placed them in a separate worksheet named `Completed Orders`.

This worksheet became the primary data source for the discount effectiveness analysis.

### 5. PivotTable Development

After preparing the completed orders dataset, I moved into the analysis stage.

I created PivotTables to summarize the data and answer the project's key business questions.

The PivotTables were structured around four major analytical areas:

1. Revenue and Profit by Discount Level
2. Profit Margin by Discount Level
3. Profit Margin by Product Category
4. Profit by Product Category

I also created separate PivotTables for the key performance indicators displayed at the top of the dashboard.

These KPI summaries provided an overview of the company's overall sales and profitability performance.

### 6. Dynamic and Interactive Chart Titles

Beyond creating the PivotTables, I used Excel formulas and functions to develop dynamic chart titles.

The titles were linked to the underlying PivotTable results, allowing them to update automatically as the analysis changed.

This made the chart titles responsive to the dashboard slicers.

Consequently, when a user filters the dashboard by product category, region, or sales channel, the chart titles adjust to reflect the selected data and updated analytical findings.

This approach makes the dashboard more informative and context-aware.

### 7. Dashboard Development

The final stage was building the interactive Excel dashboard.

The dashboard brings together the key performance indicators and four analytical visualizations in one interface.

Interactive slicers were added to allow users to explore performance across:

- Product Category
- Region
- Sales Channel

The dashboard was designed to provide management with a clear overview of discount performance, product profitability, and overall business performance.

---

## Dashboard Overview

![TechNova Gadgets Interactive Dashboard](TechNova%20Dashboard.png)

### Key Performance Indicators

The dashboard highlights five major KPIs:

| KPI | Value |
|---|---:|
| Total Revenue | ₦6.4B |
| Total Profit | ₦1.4B |
| Profit Margin | 22.12% |
| Total Discount Given | ₦400.4M |
| Total Product Line Records | 9,095 |

### Dashboard Visualizations

**1. Revenue and Profit by Discount Level**

Examines how revenue and profit vary across discount levels ranging from 0% to 25%.

**2. Profit Margin by Discount Level**

Evaluates how profit margins change across the different discount percentages.

**3. Profit Margin by Product Category**

Compares the profitability of individual product categories using their overall profit margins.

**4. Profit by Product Category**

Identifies the product categories contributing the highest and lowest amounts of total profit.

---

## Key Findings

### 1. Higher Discount Levels Are Associated with Lower Profit Margins

The analysis reveals a consistent decline in profit margin as discount levels increase.

| Discount Level | Profit Margin |
|---|---:|
| 0% | 26.66% |
| 5% | 22.70% |
| 10% | 18.89% |
| 15% | 14.11% |
| 20% | 8.18% |
| 25% | 2.68% |

The profit margin at the 25% discount level is significantly lower than the margin recorded at 0%.

This highlights the importance of evaluating the profitability implications of discounting rather than focusing on revenue alone.

### 2. Revenue Is Highest at the 0% Discount Level

The 0% discount category generated approximately ₦3.06 billion in revenue, compared with approximately ₦118.61 million at the 25% discount level.

This represents a substantial difference in observed revenue.

However, revenue differences alone do not establish which discount level is most effective. Sales volume, product mix, and total profit must also be considered.

### 3. Computer Accessories Leads in Profit Margin

Computer Accessories recorded the highest profit margin at 43.72%.

Other strong-performing categories include:

- Cables: 42.99%
- Chargers: 41.54%
- Power Banks: 40.40%

Laptops recorded the lowest profit margin at 19.15%.

This demonstrates that profitability varies significantly across product categories.

### 4. Smartphones Generates the Highest Total Profit

Smartphones generated approximately ₦820.48 million in total profit, making it the leading category by profit contribution.

Laptops followed with approximately ₦252.31 million.

Speakers recorded the lowest total profit at approximately ₦5.44 million.

An important distinction is that the category with the highest profit margin is not necessarily the category generating the highest total profit.

---

## Business Recommendations

Based on the findings, the following recommendations are proposed:

### 1. Review High-Discount Strategies

Management should carefully evaluate discounts of 20% and 25%, considering their considerably lower observed profit margins.

These discount levels should be retained only where the additional sales and total profit they generate justify the reduction in margins.

### 2. Adopt Category-Specific Discount Strategies

A uniform discount policy may not be suitable for every product category.

Management should consider differences in product profitability, pricing flexibility, and customer demand when determining discount limits.

### 3. Protect Profitability in High-Contribution Categories

Smartphones generate the highest total profit.

Management should monitor discounting in this category to avoid unnecessarily sacrificing profit on products that already make substantial contributions to overall profitability.

### 4. Investigate Low-Profit Categories

Categories such as Speakers should receive further investigation.

Management should examine their pricing structures, costs, sales volumes, and customer demand before making pricing or promotional decisions.

---

## Conclusion

The analysis reveals a clear relationship between increasing discount levels and declining observed profit margins at TechNova Gadgets.

However, the most effective discount strategy cannot be determined by profit margin alone.

Management must also establish whether higher discounts generate enough additional sales and total profit to justify the reduction in margins.

The central business lesson is:

**Discounting should be evaluated by the profit it helps generate, not merely the sales it attracts.**

---

## Project Screenshots

### 1. Interactive Dashboard

![TechNova Dashboard](TechNova%20Dashboard.png)

### 2. PivotTables and KPI Summaries

![TechNova Pivot Tables](TechNova%20Pivot%20Tables.png)

### 3. Raw Dataset

![TechNova Raw Dataset](TechNova%20Raw%20Dataset.png)

### 4. Transformed Dataset

![TechNova Transformed Dataset](TechNova%20Transformed%20Dataset.png)

---

## Tools and Techniques Used

**Tool:**
- Microsoft Excel

**Techniques:**
- Data cleaning
- Data aggregation
- Data transformation
- Data filtering
- PivotTables
- PivotCharts
- Excel formulas and functions
- Dynamic chart titles
- Interactive slicers
- KPI development
- Dashboard design
- Business analysis and data storytelling

---

## Project Files

- Excel Workbook: [Insert Excel workbook link here]
- GitHub Repository: [https://github.com/obiekwe-emmanuel/TechNova-Gadgets-Discount-Effectiveness-Analysis]

---

*This project demonstrates the application of Microsoft Excel in transforming raw sales data into meaningful business insights and actionable recommendations.*
