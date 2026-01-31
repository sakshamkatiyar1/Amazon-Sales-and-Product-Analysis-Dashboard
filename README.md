# Amazon Sales Review Dashboard
## Project Description

An interactive Power BI dashboard built to analyze and visualize sales performance data of Amazon products. This dashboard provides key insights into yearly and quarterly sales, sales trends over time, top selling products, sales distribution across product categories, and customer review performance.

## Purpose

The purpose of this project is to help stakeholders and analytics teams understand product performance, monitor sales and customer review trends, and make data-driven business decisions. The dashboard presents a clear visual analysis of sales performance across time, product categories, weeks, and reviews.

## Key Features

- Interactive Sales Overview with Year-to-Date (YTD) and Quarter sales
- Trend analysis by Month and Week to observe sales patterns
- Sales by Product Category with detailed breakdowns
- Top 5 Products by YTD Sales
- Top 5 Products by YTD Reviews
- Dynamic filters for product categories and quarterly analysis
- Custom visuals for improved insights and decision support

## Tech Stack

- Power BI Desktop – Dashboard creation and visualization
- Power Query – Data extraction and transformation
- Data Modeling – Establishing relationships between tables
- DAX (Data Analysis Expressions) – Calculation of KPIs and measures
- Excel – Source data storage 
- Git & GitHub – Version control and repository hosting

## Data Source

This dashboard uses data stored in **Excel files** exported from Amazon sales records. The Excel workbook contains structured data used to generate trends, metrics, and analytics in Power BI.

- **Format:** Excel Workbook (`.xlsx`)
- **Imported via:** Power BI *Get Data → Excel*
- **Prepared using:** Power Query for cleaning, filtering, and shaping

## Required Excel Sheets & Columns

### Sheet: Sales
- `OrderID` – Unique order identifier  
- `OrderDate` – Date of sale  
- `Product` – Product name or ID  
- `Product Category` – Category of product  
- `SalesAmount` – Sales revenue generated  
- `WeekNumber` – Week of the sale  
- `Month` – Month of the sale  
- `YTD Sales` – Year-to-Date sales measure  
- `QTR Sales` – Quarterly sales measure  
- `TotalReviews` – Number of reviews

## Screenshot

[Dashboard Preview](https://github.com/sakshamkatiyar1/Amazon-Sales-and-Product-Analysis-Dashboard/blob/main/Amazon%20Sales%20and%20Product%20Dashboard%20Screenshot%20-%20Power-BI.png)


