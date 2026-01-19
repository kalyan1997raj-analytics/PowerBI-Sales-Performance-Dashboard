**Project Overview**

This project presents an end-to-end Business Intelligence solution built using Power BI to analyze sales performance across time, product categories, customers, and regions.
The dashboard is designed from an executive decision-making perspective, focusing on KPIs, trends, and actionable insights rather than just visuals.

**Business Objectives**

Track Year-to-Date (YTD) sales, profit, quantity, and margin

Analyze sales & profit trends over time

Identify top-performing and loss-making categories/products

Understand regional and customer-level revenue concentration

Enable interactive analysis for stakeholders using slicers

**Dataset**

Source: Sample Superstore (CSV)

**Key Fields**:

Order Date, Ship Date

Sales, Profit, Quantity

Category, Sub-Category, Product

Customer, Region, State

**Data Modeling**

A Star Schema was implemented to support scalable and accurate analytics:

Fact Table: Sales

Dimension Tables:

Date (custom calendar table – mandatory for time intelligence)

Customer

Product

Region

✔ One-to-Many relationships

✔ Single-direction filtering

✔ Proper date table marked for time intelligence

**Key DAX Measures**

Some of the core measures used in this project:

Total Sales

Total Profit

Total Quantity

Profit Margin %

Sales YTD

Sales Last Year (LY)

Year-over-Year (YoY %)

% of Total Sales (Customer & Region analysis)

All measures were validated to ensure correct filter and time context.

**Dashboard Pages**

1️⃣ Executive Sales Performance Overview

KPI cards for Sales, Profit, Quantity, Margin (YTD)

Sales & Profit trends over time

Regional sales comparison

Key business insights for leadership

**Key Insights**:

Total sales increased 15% YoY, driven by strong growth in the West region

Profit margin remained stable at 12.25%

Top 3 regions contribute ~60% of total sales


2️⃣ Product & Category Analysis

Sales & Profit by Category

Profit Margin by Category

Top 10 Products by Sales

Identification of loss-making products

**Key Insights**:

Technology drives the highest revenue

Furniture shows lower margins

Several high-selling products operate at a loss, indicating pricing or cost issues


3️⃣ Regional & Customer Performance

Revenue & Profit by Region

Geographical distribution of sales

Top 10 customers by revenue

% contribution of each customer to total sales

**Key Insights**:

Revenue is concentrated in a few key regions and customers

Customer diversification could reduce revenue risk

**Tools & Technologies**

Power BI

DAX

Power Query

Data Modeling (Star Schema)

CSV Data Source

**Key Takeaways**

Demonstrates real-world BI development lifecycle

Focus on business storytelling, not just visuals

Built with best practices in data modeling and DAX

Suitable for Data Analyst / BI Analyst / Power BI Developer roles

**Dashboard Screenshots**
**Executive Sales Performance Overview**
<img width="762" height="493" alt="executive-overview png" src="https://github.com/user-attachments/assets/d3185d33-2ea2-4e9a-983e-a9197a1c64a0" />

**Product & Category Analysis**
<img width="941" height="481" alt="product-category-analysis png" src="https://github.com/user-attachments/assets/e9f6127e-1dc4-4325-9c3a-25f0b741f760" />

**Regional & Customer Performance**
<img width="795" height="492" alt="regional-customer-performance" src="https://github.com/user-attachments/assets/13f9db30-1517-4441-ad1b-97239b588b17" />


 

