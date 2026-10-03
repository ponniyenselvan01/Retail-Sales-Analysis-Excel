# Retail Sales Analysis – Excel

## Project Overview

This project analyzes retail sales data for January–March 2025 using Microsoft Excel.

The analysis focuses on sales performance, profitability, product performance, monthly trends, and city-level performance.

## Objectives

- Analyze overall sales and profit performance
- Identify the highest-performing product categories
- Analyze monthly sales trends
- Compare sales across cities
- Identify top-performing products
- Calculate key business metrics
- Build an Excel dashboard

## Tools Used

- Microsoft Excel
- PivotTables
- PivotCharts
- Excel formulas
- Git
- GitHub

## Key KPIs

- Total Sales: ₹5,44,700
- Total Profit: ₹81,400
- Total Quantity: 44
- Number of Orders: 30
- Average Order Value: ₹18,156.67
- Overall Profit Margin: 14.94%
## KPI Definitions

| KPI | Definition |
|---|---|
| Total Sales | Sum of all sales revenue |
| Total Profit | Sum of profit generated from all orders |
| Total Quantity | Total number of units sold |
| Number of Orders | Count of unique orders |
| Average Order Value | Total Sales divided by Number of Orders |
| Overall Profit Margin | Total Profit divided by Total Sales |## KPI Definitions

| KPI | Definition |
|---|---|
| Total Sales | Sum of all sales revenue |
| Total Profit | Sum of profit generated from all orders |
| Total Quantity | Total number of units sold |
| Number of Orders | Count of unique orders |
| Average Order Value | Total Sales divided by Number of Orders |
| Overall Profit Margin | Total Profit divided by Total Sales |
## Key Insights

- Electronics generated the highest sales at ₹4,02,700.
- January recorded the highest monthly sales at ₹2,16,200.
- Chennai generated the highest city sales at ₹2,31,300.
- Accessories had the highest profit margin at 28.51%.

## Dashboard

The Excel dashboard includes:

- KPI cards
- Monthly Sales Trend
- Sales by Category
- Sales by City
- Sales by Product
- Business Insights

## Project Structure

```text
Retail-Sales-Analysis-Excel/
│
├── Retail_Sales_Analysis.xlsx
├── README.md
└── .gitignore
```

## Analysis Methodology

### 1. Data Preparation

- Converted the raw dataset into an Excel Table named `SalesData`.
- Checked the dataset for missing values.
- Checked Order_ID values for duplicates.
- Verified appropriate data types for dates, text, and numeric fields.
### Data Quality Checks

The following checks were performed before analysis:

- Checked the dataset for blank cells in the original data fields.
- Checked Order_ID values for duplicate records.
- Verified that dates were stored as valid Excel dates.
- Verified that Quantity, Sales, and Profit were numeric values.
- Confirmed that the dataset contains 30 unique orders.
### 2. Calculated Columns

Two calculated columns were added:

- Profit_Margin = Profit / Sales
- Month = Month extracted from the Date field

### 3. KPI Analysis

The following KPIs were calculated:

- Total Sales
- Total Profit
- Total Quantity
- Number of Orders
- Average Order Value
- Overall Profit Margin

### 4. Business Analysis

Sales and profit were analyzed by:

- Category
- Month
- City
- Product

### 5. Visualization

PivotTables and PivotCharts were created to visualize:

- Monthly sales trends
- Sales by category
- Sales by city
- Sales by product

### 6. Dashboard

The final Excel dashboard combines:

- KPI cards
- Four sales charts
- Business insights