# Final_Project_PowerBI_Excel
# Sales Performance Analysis | Excel + Power BI

## Overview
An end-to-end analysis of a global sales dataset (Kaggle, ~51K orders). I cleaned the data in Excel and built a 3-page interactive dashboard in Power BI covering sales, profitability, and customer & operations.

## Business Questions
- Which regions and categories drive the most sales and profit?
- Which products or regions are losing money or have weak margins?
- How have sales and profit changed over time?
- Who are the key customers and which segments are the largest?

## Tools Used
- **Excel:** data cleaning and preparation
- **Power BI:** data modelling, DAX measures, visualization, slicers

## Data Cleaning Steps (Excel)
- Removed duplicate records
- Handled missing values
- Standardized date and number formats

## Dashboard Pages
### 1. Sales Performance
KPIs: Total Sales (12.65M), Total Profit (1.47M), Total Orders (51K)
Visuals: sales by region, sales trend over time, sales by category, region slicer

### 2. Profitability
KPIs: Profit Margin (~12%), Profit per Order (28.62)
Visuals: profit by region, profit trend, profit by sub-category

### 3. Customer & Operations
KPIs: Total Shipping Cost (1.35M), Total Customers (1,590), Total Quantity Sold (178K)
Visuals: order priority distribution, customers by segment, top 10 customers by sales

## Key Insights
- Sales nearly doubled to about 4.0M in the most recent year shown.
- Central is the top region by sales (2.8M) and profit (0.31M).
- Technology is the top category by sales (4.7M).
- Tables are loss-making (-0.06M profit).
- Southeast Asia and EMEA have very low profit margins relative to their sales.
- The top 10 customers contribute only about 2.5% of sales, so revenue is not concentrated.

## Recommendations
- Review pricing and discounts on Tables.
- Investigate cost drivers in low-margin regions (e.g., shipping).
- Focus growth on high-margin regions and categories.

## Dashboard Screenshots
<img width="1327" height="738" alt="Screenshot 2026-11-21 184503" src="https://github.com/user-attachments/assets/c3300e1c-ff24-41b4-8daf-f794db5e9829" />
<img width="1325" height="745" alt="Screenshot 2026-11-21 184537" src="https://github.com/user-attachments/assets/e4a73a11-79ba-4911-a0d2-2645569b0c54" />
<img width="1323" height="740" alt="Screenshot 2026-11-21 184557" src="https://github.com/user-attachments/assets/671f6734-4986-4bfa-b90c-163166b6b670" />

## Files
- `Mini Project Excel.xlsx`: cleaned dataset
- `Mini Project.pbix`: Power BI dashboard file
