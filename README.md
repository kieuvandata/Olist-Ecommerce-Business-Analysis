# Olist-Ecommerce-Business-Analysis
Data-driven insights into 100k+ Brazilian e-commerce orders to improve delivery efficiency.
# Project Overview
This project focuses on analyzing the business health and operational efficiency of Olist, a leading e-commerce platform in Brazil. By deep-diving into over 100,000 orders , the objective is to monitor sales performance, understand customer behavior, and identify critical "bottlenecks" in the logistics process to improve delivery times.
Dataset: Brazilian E-Commerce Public Dataset by Olist (2016-2018).  
Key Focus: Logistics performance and regional delivery optimization.
# Tech Stack & Data Modeling
Tool: Power BI.
Modeling Strategy: Implemented a Star Schema architecture to ensure high performance and scalability.  
Fact Table: olist_order_items (Transaction details).  
Dimension Tables: Dim_Orders (Status/Time), Dim_Products, Dim_Customers, and Dim_Sellers.  
DAX (Data Analysis Expressions): Developed custom measures for dynamic KPI tracking and a specialized Date Table for time-series analysis.
Key Performance Indicators (KPIs)
The dashboard tracks vital metrics to evaluate operational success:  
Total Revenue: Total transaction value of successful deliveries.  
Total Orders: Total unique orders placed on the system.  
Avg. Delivery Time: Average days from order placement to customer receipt.  
% Late Orders: The percentage of orders delivered past the estimated date (reflecting service quality).  
Avg. Ticket Size: Average revenue generated per order.
