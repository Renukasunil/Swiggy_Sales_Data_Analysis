# Swiggy Sales Data Analysis Dashboard
## Project Overview
This project analyzes Swiggy sales data to identify key revenue patterns, customer demand trends, and regional performance.
An interactive Power BI dashboard was created to visualize daily, monthly, and category‑wise sales insights, helping stakeholders understand overall business performance.

## Dataset Description
### The dataset contains sales and rating information with the following columns:
State – State where the order was placed<br>
City – City of the order<br>
Order Date – Date of the order<br>
Restaurant Name – Restaurant fulfilling the order<br>
Location – Restaurant location<br>
Category – Food category<br>
Dish Name – Name of the dish<br>
Price (INR) – Order value<br>
Rating – Customer rating<br>
Rating Count – Number of ratings received<br>
###### Note: As the dataset does not contain an Order ID, each row is assumed to represent one order.

## Objectives
Analyze total sales and order trends<br>
Identify top‑performing cities and food categories<br>
Understand daily and monthly revenue patterns<br>
Build easy‑to‑interpret KPIs and interactive visuals<br>

## Key KPIs Created
Total Orders<br>
Total Revenue (INR)<br>
Average Order Value (AOV)<br>
Average Rating<br>
Total Rating Count<br>

## Dashboard  Analysis
#### Daily Revenue Trend
Extracted Day Name from Order Date
Analyzed revenue distribution from Monday to Sunday
Used a Clustered Bar Chart to identify high‑revenue days
#### Monthly Sales Trend
Evaluated month‑wise revenue patterns to understand seasonality
#### Sales by Food Category
Compared revenue contribution across food categories
Identified major categories contributing a significant share of total sales
#### Top 5 Cities by Sales
Used Top N filtering in Power BI
Highlighted cities contributing the highest revenue
#### State‑wise Quarterly Performance
Analyzed regional sales trends over quarters

## Tools & Techniques Used
Python<br>
Power BI<br>
DAX (Measures & Calculated Columns)<br>
Clustered Bar Charts, Donut Charts<br>
KPI Cards<br>
Slicers and Filters<br>

## Power BI DashBoard
<img width="400" height="250" alt="Screenshot (32)" src="https://github.com/user-attachments/assets/eb14bafd-8df9-4107-9afc-6458dbf39be2" />


## Assumptions
Each record represents a single order<br>
Revenue analysis is based on Price (INR)<br>
Dataset is intended for analytical and learning purposes<br>

## Key Insights
<b>City‑wise Revenue Concentration</b>: A limited number of cities contribute a major share of total sales, indicating strong demand in urban markets.<br>
<b>Food Category Performance</b>: Certain food categories consistently generate higher revenue, reflecting clear customer preferences.<br>
<b>Day‑wise Sales Variation</b>: Revenue fluctuates across weekdays, with specific days showing higher order volume and value.<br>
<b>Monthly Trends</b>: Sales patterns vary month‑to‑month, indicating seasonal and behavioral demand shifts.<br>
<b>Customer Engagement</b>: Cities with higher order volumes also show higher rating counts, indicating stronger customer engagement.<br>

## Recommendations
Prioritize High‑Revenue Cities: Focus marketing and operations on top‑performing cities to maximize impact.<br>
Strengthen High‑Demand Categories: Promote best‑performing food categories while improving visibility of others.<br>
Plan Operations by Demand Patterns: Optimize staffing and delivery resources based on daily sales trends.<br>
Leverage Seasonal Opportunities: Align campaigns and offers with high‑growth months.<br>
Use Ratings for Improvement: Monitor ratings to identify high‑quality restaurants and improve underperformers.<br>




























