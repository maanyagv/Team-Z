Project Description

This project presents a comprehensive Retail Inventory, Demand, and Stockout Analysis Dashboard built using Tableau.
The goal is to support retail decision-makers in understanding product availability, forecasting demand, identifying stockout risks, and optimizing inventory replenishment.
To build this dashboard, we used the Retail Store Inventory Forecasting Dataset from Kaggle:

🔗 Dataset Link:
https://www.kaggle.com/datasets/anirudhchauhan/retail-store-inventory-forecasting-dataset

This dataset contains over 180,000+ rows covering multi-store, multi-SKU daily inventory activity.
It includes historical data on:

•	Inventory levels
•	Customer demand
•	Sales performance
•	Replenishment quantities
•	Pricing and discount patterns
•	Holiday/promotion effects
•	Competitor pricing
•	Product classification and store segmentation

Using this rich dataset, we created an end-to-end Tableau solution that delivers deep operational insights.

What Our Dashboard Provides

Our Tableau dashboard is designed as a complete decision-support system for retail inventory management.
It contains multiple analytical components:

1.	KPI Summary Dashboard

A top-level view of the most important daily/weekly inventory metrics:

•	Stockout Cost – financial loss due to unavailable products
•	Lost Sales – demand that could not be met
•	Fill Rate – % of customer demand satisfied
•	Inventory Turnover – how fast inventory cycles
•	DIOH (Days Inventory on Hand) – inventor coverage
•	Carrying Cost – cost of storing excess inventory
•	SKU Value – financial value of stock on hand

 Helps leadership quickly evaluate operational performance.

2.	Inventory Trend & Stock Health

•	Tracks how inventory changes over time:
•	Daily inventory levels per SKU/store
•	Low-stock warnings
•	Replenishment cycles
•	Overstock vs understock patterns

 Ensures better planning of purchase orders and warehouse management.

3.	Demand vs Inventory Gap Analysis

Compares customer demand to actual available stock:

•	Real demand vs. fulfilled demand
•	Forecasted demand
•	Impact of competitor pricing
•	Effect of discounts and promotions

 Highlights mismatches that lead to stockouts or lost revenue.

4.	Stockout Analysis Dashboard

•	Identifies stockout patterns, including:
•	Stockout count per SKU/store
•	Stockout flag timeline
•	Stockout heatmap
•	Customer demand during stockout periods
•	Stockout cost estimation

 Helps discover WHY stockouts happen and which products are most affected.

5.	SKU Performance Dashboard

•	Deep dive into each product’s performance:
•	Units Sold vs Units Ordered
•	Price → Demand relationship
•	Discount impact
•	Revenue contribution
•	Fast vs slow-moving SKUs

Helps choose the right assortment, pricing, and promotion strategy.

Calculated Fields Used in the Dashboard

We created multiple custom calculated fields in Tableau, including:

•	Stockout Flag
•	Stockout Count
•	Stockout Cost
•	Lost Sales
•	Fill Rate
•	Carrying Cost
•	SKU Value
•	Inventory Turnover
•	DIOH
•	Demand Forecast
•	Holiday/Promotion Effect
•	Competitor Pricing Impact
•	Units Sold vs Units Ordered Metrics

These are stored in the tableau/calculated_fields folder.

Overall Project Purpose

The objective of this project is to:

•	Reduce stockouts and lost sales
•	Improve forecasting and replenishment decisions
•	Detect demand surges due to promotions or competitor pricing
•	Monitor product performance across multiple stores
•	Build an easy-to-understand dashboard for retail teams
•	Support data-driven inventory planning

Our solution enables retailers to answer critical questions such as:

•	Which SKUs are driving the highest losses due to stockouts?
•	Is inventory being replenished efficiently?

•	How do promotions impact demand?
•	Which SKUs require immediate stock review?
•	Where can inventory be optimized to reduce costs?

 Final Output

A fully interactive Tableau dashboard that retail managers can use daily to improve:

•	Stock planning
•	Demand forecasting
•	Purchasing strategy
•	Warehouse operations
•	Store replenishment cycles
