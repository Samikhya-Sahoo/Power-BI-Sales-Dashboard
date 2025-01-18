# Sales Insight Dashboard in Power BI

This repository contains a **Sales Insight Dashboard** created in Power BI to provide a comprehensive analysis of revenue and sales data across various dimensions such as market, customers, products, and timeline. Unlike the earlier dashboard, this one is built without dynamic parameters but focuses on static insights with advanced data modeling.

---

## Dashboard Screenshot

![Sales Insight Dashboard](https://github.com/Samikhya-Sahoo/Financial-Dashboard-in-Power-BI/blob/main/Sales_Insight_Dashboard.png)

---

## Key Features

- **Revenue and Sales Quantity Insights**:
  - Displays total revenue and total sales quantity at the top of the dashboard.

- **Revenue by Market**:
  - Visualizes revenue generated from various markets like Delhi NCR, Mumbai, Ahmedabad, and others using a bar chart.

- **Total Quantity by Market**:
  - Analyzes the total sales quantity across different markets.

- **Top 5 Customers and Products**:
  - Highlights the top-performing customers and products contributing to revenue.

- **Revenue by Timeline**:
  - A line chart tracks revenue trends across months and years, providing time-series insights.
 
---
## Data Modeling

The data model for this dashboard includes the following key tables and relationships:
1. **Base Measures**:
   - Pre-calculated measures for revenue, sales quantity, and other KPIs.

2. **Sales Customers**:
   - Contains customer-specific details.

3. **Sales Markets**:
   - Includes market-specific data.

4. **Sales Products**:
   - Information about product codes and categories.

5. **Sales Transactions**:
   - Contains transactional data, including dates and values.

**Modeling Approach**:
- The relationships between tables are designed to enable seamless cross-filtering and aggregation in visualizations.
- Star schema structure is applied to ensure optimized performance.

---

## Data Source

The data for this dashboard was extracted from an SQL database. Key tables were queried and imported into Power BI for further processing and modeling.
You can access the dataset [here](https://github.com/Samikhya-Sahoo/Power-BI-Sales-Dashboard/blob/main/db_dump%20Dataset.sql).


