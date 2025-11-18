# PowerBI-Sales-Analytics-DataModeling
This project applies Power BI data modeling and DAX analytics to analyze sales performance across products, regions, dates, and sales teams. The goal is to practice building a star schema, perform data transformations, create DAX measures, and answer real business questions using interactive visualizations.


## Major Transformation Steps
# 1. Data Import & Cleaning

Loaded all tables (Sales, Products, Region, Salesperson, Date).

Validated data types, fixed formatting issues, and removed duplicates.

Ensured key fields (ProductKey, EmployeeKey, SalesTerritoryKey, OrderDate) were consistent across tables.

# 2. Data Modeling (Star Schema)

Built a star schema with Sales as the central fact table.

Connected lookup tables using correct key relationships.

Marked the Date table as the official date table for time-intelligence functions.

# 3. DAX Measures & Calculations

Created core measures like Sales Amount, YoY growth, MTD/QTD/YTD sales, and rolling totals.

Added filters for product color, category, region, and salesperson.

Used advanced functions (RELATED, RELATEDTABLE, CROSSFILTER, USERELATIONSHIP) to support analysis.

# 4. Business Questions & Insights

Answered questions on product performance, regional trends, salesperson results, and time-based patterns.

Identified top-selling categories, unsold products, and non-US revenue.

Built visuals (charts, tables, cards) to communicate findings clearly.

