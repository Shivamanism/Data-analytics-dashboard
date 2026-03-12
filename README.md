# data-analytics-dashboard
ShopNest Store Sales Analysis Dashboard

**Project Overview**

ShopNest is a leading e-commerce marketplace that connects small businesses with customers across Portugal. This project focuses on analyzing ShopNest’s transactional data to uncover valuable insights into sales performance, customer behavior, order delivery efficiency, and revenue trends.

An interactive dashboard was developed using Power BI to transform raw data into meaningful visual insights that support better business decision-making.

**Project Objectives**

* Analyze overall sales performance and revenue trends.
* Identify top-performing product categories contributing to total sales.
* Evaluate delivery performance by analyzing delayed orders.
* Understand customer payment preferences.
* Analyze product ratings to identify high- and low-performing products.
* Perform regional sales analysis to identify high-revenue states.
* Detect seasonal sales trends across months and quarters.
* Build an interactive dashboard to support business insights.

**Data Preparation and Modeling**

The dataset was cleaned, transformed, and modeled before visualization.

**Data Preparation**

Removed duplicate records and handled missing values.
Converted date columns into proper date formats.
Created calculated columns for delivery status (Delayed / On-Time).
Standardized product category and payment method fields.

**Data Modeling**

Built relationships between tables such as:

Established relationships between tables such as Orders <-> Customers orders <-> Product orders <-> Payments orders <-> Reviews orders <-> Sellers. This structured data model enabled efficient cross-table analysis and significantly improved query performance.Created a star schema model to improve performance and query efficiency.
In this project. 

**Key Metrics and DAX Calculations**

Several DAX measures were created to evaluate business performance.

Revenue Metrics: 

  - Total Revenue.
  - Average Order Value.
 - Revenue by Region.
 - Revenue by Product Category.

Operational Metrics:

- Total Orders.
- Delayed Orders.
- On-Time Delivery Time.

Customer Metrics:  

- Average Customer Rating.
- Review Distribution.
- Customer Satisfaction Trends.

**Key Insights**

* A small number of product categories contribute significantly to total revenue.
* Certain regions show higher sales concentration, indicating strong regional demand.
* A portion of orders experience delivery delays, highlighting potential logistics inefficiencies.
* Digital payment methods are the most preferred among customers.
* Highly rated products tend to correlate with higher sales performance.

**Business Impact**

* Helps management identify top-performing products and categories.
* Enables tracking of delivery delays to improve logistics performance.
* Supports regional sales strategy and targeted marketing campaigns.
* Provides insights into customer preferences and satisfaction levels.
* Enables data-driven decision making through interactive dashboards.

**Tools and Technologies**

Power BI

DAX(Data Analysis Experssions).

Data Modeling. 

Business Intelligence Visualization.


