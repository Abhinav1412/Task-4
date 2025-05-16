Sales Dashboard (Power BI)

About the Project:
This project was part of a Data Analyst internship task. The goal was to create an interactive sales dashboard using Power BI that would help business users explore key metrics like sales, profit, and performance across categories, time, and regions.

Dataset:
- Name: Sales Dataset from Kaggle
- Records: 1,194 rows
- Main fields: Amount, Profit, Quantity, Category, Sub-Category, Payment Mode, Order Date, City, State
- Time range: 2021 to 2024 (based on Order Date and Year-Month)

Tools Used:
- Power BI Desktop for dashboard design
- DAX to calculate KPIs
- Standard Power BI visuals (cards, line charts, bar charts, maps)
- Slicers to make the dashboard interactive

What's in the Dashboard:

KPI Cards:
- Total Sales – Sum of all sales amounts
- Total Profit – Total profit from all orders
- Total Quantity – Total number of items sold
- Profit Margin – Calculated using DAX: Profit ÷ Sales

Trend Over Time:
- A line chart that shows how sales and profit changed over time (Year-Month)

Category Breakdown:
- Bar charts showing sales and profit by Category and Sub-Category

Regional View:
- A map showing total sales by State
- 
Filters/Slicers:
- Order Date
- Category
- State
- Payment Mode

DAX Measures
Profit Margin = DIVIDE(SUM('Sales Dataset'[Profit]), SUM('Sales Dataset'[Amount]), 0)

What I Learned:
- How to turn raw data into something visually meaningful
- Writing simple DAX formulas for key metrics
- Making dashboards interactive with slicers and filters
- Presenting data clearly for business users

Credits:
Abhinav Srivastava
Task 4 – Data Analyst Internship
May 2025
