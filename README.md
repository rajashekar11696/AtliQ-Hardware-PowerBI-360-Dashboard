# AtliQ Hardware - Business Insights 360 Dashboard

Welcome to the Business Insights 360 Dashboard project! This project showcases an end-to-end business intelligence solution for AtliQ Hardware, a fictional consumer electronics company. By leveraging Power BI, this project aims to address real-world business challenges and provide advanced reporting and visualization.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Problem Statement](#problem-statement)
3. [Data Model](#data-model)
4. [Dashboards Overview](#dashboards-overview)
5. [Key Insights](#key-insights)
6. [Technologies Used](#technologies-used)
7. [Project Highlights](#project-highlights)
8. [How to Use the Dashboards](#how-to-use-the-dashboards)
9. [Conclusion](#conclusion)

## Project Overview

AtliQ Hardware, a rapidly growing company, faced significant challenges with data analysis due to reliance on Excel. This project implements a comprehensive data analytics solution using Power BI, aimed at overcoming these limitations and addressing financial losses, particularly in the Latin American market.

The solution includes:
- Customized Profit & Loss (P&L) reports
- In-depth financial, sales, marketing, and supply chain insights
- Executive summaries for strategic decision-making

## Problem Statement

With growth exposing gaps in their data analytics, AtliQ Hardware’s reliance on Excel became cumbersome. The lack of dynamic insights led to substantial losses, especially in Latin America. To address these issues, a robust data analytics system was developed to empower teams with actionable insights and data-driven decisions.

## Data Model

The data model follows a Star Schema to support efficient data aggregation and analysis:

- **Fact Table**: Contains core business data such as Sales, Costs, and Quantities.
  - Measures: Net Sales, Gross Margin, Operational Expenses.
- **Dimension Tables**:
  - Time Dimension: Date, Fiscal Year, Fiscal Month.
  - Product Dimension: Product Code, Category, Division, Variant.
  - Customer Dimension: Customer Code, Target, Market.
  - Geography Dimension: Sub-Zone, Market.
  - Hierarchy: Category, Product, Customer-specific views.
  - Additional Dimensions: Discounts, Promotions, Operational Expenses.

## Dashboards Overview

### 1. Home Dashboard
**Description**: Central hub for navigating various business functions.
- **Key Features**: Customizable P&L statements, comprehensive metrics, user assistance.
- **Use Cases**: Generate P&L statements, assess sales performance.

### 2. Finance View
**Description**: Detailed financial analysis.
- **Key Metrics**: Net Sales, P&L Breakdown, Top/Bottom Products & Customers.
- **Key Insights**: YoY sales decline, stable gross margin, rising operational expenses.

### 3. Sales View
**Description**: Customer and product-level sales analysis.
- **Key Components**: Customer Performance Matrix, Top Customers, Product Performance.
- **Key Insights**: Post-invoice deductions as a major cost opportunity.

### 4. Executive View
**Description**: High-level business summary for executives.
- **Key Features**: YoY comparisons, geographic breakdown, top customers/products.

### 5. Marketing View
**Description**: Sales and market share analysis from a marketing perspective.
- **Key Metrics**: Customer segmentation, market share, cost structure.

### 6. Supply Chain View
**Description**: Inventory and forecast accuracy analysis.
- **Key Metrics**: Forecast accuracy, excess inventory.

### 7. Support Dashboard
**Description**: Provides user assistance and support resources.

## Key Insights
1. **Net Sales Decline**: Address pricing, customer relations, and marketing strategies.
2. **Gross Margin Consistency**: Effective cost management despite sales declines.
3. **Operational Expenses**: Increased costs affecting net profit, needing efficiency improvements.
4. **Supply Chain Risks**: Enhance forecast accuracy to reduce excess inventory and avoid stockouts.

## Technologies Used
- **Power BI**: For interactive dashboards and visualizations.
- **Star Schema**: Data model for efficient analysis.
- **Excel**: Data pre-processing.
- **DAX**: For measures and KPIs.
- **SQL**: For data extraction, transformation, and loading.

## Project Highlights
- Transitioned from Excel-based analysis to Power BI dashboards.
- Enabled real-time, interactive insights across Finance, Sales, Marketing, and Supply Chain.
- Created a modular structure for detailed business function analysis.

## How to Use the Dashboards
1. **Home Dashboard**: Entry point to access other dashboards.
2. **Drill Down**: Navigate between dashboards for specific insights.
3. **Filters**: Customize views based on time periods, products, customers, and regions.

## Conclusion

This project illustrates the power of data analytics in transforming business performance. By utilizing Power BI and advanced data modeling, it provides a comprehensive view of AtliQ Hardware’s operations, supporting strategic decision-making.

I welcome any feedback or suggestions to further enhance this solution.
