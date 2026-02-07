# CTH-mentorship-Global-Superstore-Project
Project Overview:
This project presents an end-to-end business intelligence and data analytics solution built using the Kaggle Global Superstore dataset. The objective is to analyze sales performance, customer behavior, and profitability patterns across global markets, and to communicate insights through interactive dashboards and visual storytelling.
The analysis follows best practices in data modeling, descriptive, diagnostic, predictive, and prescriptive analytics, and dashboard design using Microsoft Excel and Power Query.

Dataset Description:
The dataset contains detailed transactional records of a global retail superstore, including:
Orders, sales, profit, discounts, and shipping costs
Product categories and sub-categories
Customer segments and identifiers
Geographic information (market, region, country, city)
Time attributes (order date, ship date, year, week number)

Source: Kaggle – Global Superstore Dataset

Data Modeling & Preparation:
Data cleaning and transformation were carried out using Power Query.
To ensure analytical accuracy and performance, the dataset was modeled using a star schema.

Fact Table:
Orders: Sales, Profit, Quantity, Discount, Shipping Cost
Order Date, Ship Date
These are foreign keys linking to dimensions

Dimension Tables:
Customers – customer_id, customer_name, segment
Products – product_id, product_name, category, sub_category
Location – market, region, country, state, city

This structure prevents data duplication, avoids many-to-many joins, and enables efficient slicing and aggregation.

Types of Analysis Performed:
1️. Descriptive Analytics (What happened?)
Sales and profit trends over time
Category and sub-category performance
Market-level sales and profitability distribution

2️. Diagnostic Analytics (Why did it happen?)
Identification of loss-making products
Comparison of profitability across markets and shipping modes

3. Predictive Analytics (What is likely to happen?)
Sales and profit forecasting using historical trends

4️. Prescriptive Analytics (What should be done?)
Recommendations for product portfolio optimization
Market prioritization for expansion
Customer sales distribution for diversification and growth
Shipping mode optimization to improve margins

Dashboard Features:
The Excel dashboard is fully interactive and includes:

KPI cards for Sales, Profit, and Orders,etc
Time-series charts with trend analysis
Category and sub-category performance visuals
Market and regional comparison charts
Customer Sales Distribution by Segment
Shipping mode profitability analysis

Synced slicers across sheets for:
Year
Category
Customer Segment
Shipping Mode

Slicers are connected using the Excel Data Model, ensuring consistent filtering across all dashboard pages.

Key Insights:
Profitability increased consistently between 2011 and 2014
Technology products are the primary revenue drivers
Some sub-categories generate losses despite high sales volume
APAC is the most profitable global market
Shipping mode choice has a measurable impact on profit margins
Consumer segment drives the majority of revenue while Corporate and Home Office segments present opportunities for strategic growth and diversification.

Tools & Technologies:
Microsoft Excel
Power Query
Excel Data Model & PivotTables
GitHub

How to Use This Project:
Download or clone the repository
Open the Excel dashboard file
Use slicers to explore sales, customer, product, and market insights
Review the PowerPoint presentation for summarized findings and recommendations

Learning Outcomes

This project demonstrates:
Practical application of data analytics concepts
Proper dimensional modeling in Excel
Business-driven dashboard design
Clear communication of insights and recommendations
