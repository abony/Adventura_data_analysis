# Adventura Data Analysis

Adventura Pvt. Limited -
Customer Segmentation and Sales Performance Analysis
<div align="center">
  <img alt="Adventura_logo" src="https://github.com/user-attachments/assets/d47addc8-e1df-40a5-8389-a3b84c214155" width="300"/>
</div>

Introduction
This project analyzes Adventura Pvt. Limited's historical sales and customer data of 100,000 Orders to identify key customer segments, evaluate marketing campaign effectiveness, and provide actionable recommendations to increase revenue and optimize future marketing spend. The primary goal was to shift away from broad marketing efforts to a data-driven, targeted approach.

Data Source

Source data was a proprietary sales database containing tables: Sales, Transactions, Customer Demographics, Product categories and Subcategories, Return Data etc.
The dataset covered sales from January 2020 to June 2022.

Tools, Technologies, Analysis & Visualization

Microsoft Excel
Power BI (primary tool)
Advanced Calculations: DAX (for measures to be used for analysis)
Documentation: Microsoft Word for Markdown

Data Preparation

Performed ETL (Extract, Transform, Load) processes to merge more than 5 tables into a cohesive star schema model in Power BI. Key transformations included: Handling nulls in the Customer Occupation field, standardizing date formats, and creating a calendar table for time-intelligence analysis.
Created several complex DAX measures, including a time-intelligent Year-over-Year (YoY) Growth.

Insights

1. Road Bikes from Bikes Category generate the most revenue for the company and to target them for cross-selling of products
2. The Customers with Occupation as Professionals with Average Income Level generate the most revenue. This tells you the demographic to target with personalized offers or who to prioritize in acquisition / Marketing campaigns.
3. The Total Orders after the period of July 2021 spiked immediately, providing direct evidence of any campaigns which could have been led by the marketing team.
4. The bar chart in the Dashboard Filtered to show which product categories professionals spend the most on. Since Accessories is highest, your personalized outreach to Professionals should exclusively promote Accessories. This will optimize campaign relevance.

Recommendations

1. Marketing Strategy 

- The 'Average' Income segment (comprising 46% of customers) accounts for 49% of total revenue. Their purchases are concentrated in high-margin products like 'Road Bikes’.
- Reallocation of the marketing budget to personalized email campaigns targeting the ‘Average’ income segment with exclusive offers on new high-margin products, aiming for a 15% increase in AOV (Average Order Value)

2. High Margin Product Opportunity

- While Bikes drive the highest total revenue, they yield a Gross Margin of only 41.74%. Conversely, the Accessories category, despite having a smaller revenue contribution, maintains an extremely high 67.88% Gross Margin.
- This high profitability suggests that cross-selling and bundling accessories with every major purchase should be a core strategy to immediately boost overall company profit
- Integrate accessories more aggressively into the sales process. Train sales staff and optimize the e-commerce checkout flow to always cross-sell at least two high-margin accessory items to every customer purchasing a Bike.
