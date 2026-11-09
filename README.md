                                     ☕ Blue Tokai Coffee Shop Sales Analysis | Power BI

📌 Project Overview
This project focuses on analysing coffee shop sales data using Microsoft Power BI to understand business performance, customer purchasing behaviour, product sales and store-level performance.

The objective is to transform raw transaction data into an interactive dashboard that helps identify sales trends, top-performing products, store contributions and opportunities for business improvement.

The analysis covers the period January 2023 to June 2023.

🎯 Business Objectives
The project aims to answer the following business questions:

How is the coffee shop performing overall?
How do weekday and weekend sales compare?
How are daily sales changing over time?
Which product categories contribute most to monthly sales?
Is the business growing month over month?
How much do individual store locations contribute to total orders?
Which product types generate the highest revenue?
🛠️ Tools and Technologies
Tool

Purpose

Microsoft Power BI Desktop

Dashboard development and data visualization

Power Query

Data preparation and transformation

DAX

Measures, calculations and time intelligence

Data Modelling

Relationships between transaction and date tables

GitHub

Project documentation and portfolio presentation

📂 Dataset Overview
The project uses coffee shop transaction data containing sales, product, store and transaction-related information.

Key Transaction Table Columns
Column

Description

transaction_id

Unique transaction identifier

transaction_date

Date of the transaction

transaction_time

Time of the transaction

transaction_qty

Quantity of items purchased

unit_price

Selling price per unit

product_id

Product identifier

product_category

Product category

product_type

Product type

product_detail

Detailed product description

store_id

Store identifier

store_location

Store location

Sales

Sales-related field in the model

🧹 Data Preparation and Modelling
The following preparation and modelling steps were completed:

Reviewed the transaction dataset and its available columns.
Created a dedicated Date table using DAX.
Established a relationship between the Date table and Transactions table.
Configured the relationship as one-to-many, with the Date table on the one side and Transactions on the many side.
Ensured that both relationship columns used the Date data type.
Marked the Date table using its Date column.
Created a Month Start calculated column to support monthly analysis and comparison.
Created a Day Type column to classify dates as Weekday or Weekend.
The Date table supports time-based analysis and allows the Month slicer to filter the dashboard.

📊 Key Performance Indicators (KPIs)
The dashboard includes five primary KPI cards:

KPI

Result

Business Purpose

Total Sales

698.81K

Measures overall revenue

Total Orders

149K

Measures order volume

Total Quantity Sold

214K

Measures total items sold

Average Order Value

4.69

Measures average spending per order

Average Items per Order

1.44

Measures average basket size

These indicators provide a quick overview of the business’s overall performance.

📈 Dashboard Visualizations
The dashboard contains six main analytical visuals.

1. Weekday vs Weekend Sales — Donut Chart
Business Question: Does revenue come mostly from weekdays or weekends?

Compares sales generated on weekdays and weekends.
Displays the total sales value in the centre of the donut chart.
Weekday sales contribute approximately 72.06%.
Weekend sales contribute approximately 27.94%.
Business Insight: Weekdays contribute a larger share of total sales. Comparing sales per operating day can help improve staffing and promotional planning.

2. Daily Sales Trend — Line Chart
Business Question: How are daily sales moving over time?

Displays daily sales from January to June 2023.
Highlights the overall sales trend and daily fluctuations.
Business Insight: The chart shows an overall upward sales trend across the analysis period. Monitoring daily fluctuations can help with inventory and staffing decisions.

3. Category Sales Ranking by Month — Ribbon Chart
Business Question: Which product categories lead each month, and how do their positions change?

Compares product category sales across six months.
Highlights changes in category contribution and relative ranking.
Business Insight: This visual helps identify categories that maintain strong sales performance and those whose relative contribution changes over time.

4. Monthly Sales vs Previous Month Sales — Clustered Column Chart
Business Question: Is the business growing month over month?

Compares current-month sales with previous-month sales.
Uses DAX time-intelligence calculations.
Makes monthly changes easier to identify.
Business Insight: Sales show an overall upward pattern towards June, although individual months may fluctuate.

5. Order Contribution by Store Location — Column Chart
Business Question: How much does each store contribute to total orders?

The dashboard compares three locations:

Hell’s Kitchen — approximately 51K orders
Astoria — approximately 51K orders
Lower Manhattan — approximately 48K orders
Business Insight: Order volumes are relatively evenly distributed across the three locations. Lower Manhattan is slightly behind the other two stores.

6. Top 10 Product Types by Sales — Horizontal Bar Chart
Business Question: Which product types generate the highest revenue?

The leading products visible in the dashboard include:

Product Type

Approximate Sales

Barista Espresso

91K

Brewed Chai Tea

77K

Hot Chocolate

72K

Gourmet Brewed Coffee

70K

Business Insight: These leading products are important candidates for inventory planning, product availability and potential promotional bundles.

💡 Overall Business Insights
Based on the dashboard analysis:

The business generated approximately 698.81K in sales across 149K orders.
Weekdays contributed approximately 72.06% of total sales.
Sales showed an overall upward trend from January to June 2023.
Order contribution was relatively balanced across the three store locations.
A small group of product types generated comparatively high revenue.
Average items per order stood at 1.44, highlighting an opportunity to encourage additional purchases.

🚀 Business Recommendations
Based on the findings, the following actions could be considered:

Increase basket size: Test coffee-and-pastry combinations and other complementary product bundles.
Improve staffing plans: Use weekday and weekend demand patterns to support staff scheduling.
Maintain product availability: Prioritise inventory planning for high-revenue products.
Review store performance: Investigate differences in order volume across locations.
Monitor monthly performance: Continue tracking sales against previous-month results.
These recommendations should be tested against future sales data to measure their actual impact.

📷 Dashboard Screenshots
Full Dashboard View
<!-- Add your main Power BI dashboard screenshot below this heading -->
Screenshot 1 – Overall Dashboard

Additional Dashboard Views
<!-- Add additional screenshots below when available -->
Screenshot 2 – KPI Cards and Sales Performance

Screenshot 3 – Product and Store Analysis

📁 Project Files
The repository is intended to contain the following project materials:

Power BI dashboard file (.pbix)
Project report (.pdf)
Dashboard screenshots (.png)
README documentation (README.md) 

📚 Key Learnings
Through this project, I gained practical experience in:

Preparing and understanding business transaction data.
Creating and managing relationships between tables.
Developing DAX measures for business KPIs.
Applying time-intelligence functions for month-over-month analysis.
Building interactive dashboards using Power BI.
Translating analytical results into meaningful business insights.
Presenting findings through data visualizations and recommendations.

👨‍💻 Author
Sai Sandeep Kuchupudi 

Aspiring Data Analyst | Power BI | SQL | Excel | Python


Thank you for visiting my project!

