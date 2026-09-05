# 🚚 Supply Chain Control Tower Dashboard

### Advanced Power BI Analytics Solution

An interactive end-to-end analytics solution for monitoring **sales, profitability, customer behavior, shipping performance, delivery efficiency, and operational risks**.

**Built with:** Power BI • Power Query • DAX • Star Schema

![Power BI](https://img.shields.io/badge/Power%20BI-Analytics-yellow)
![DAX](https://img.shields.io/badge/DAX-Business%20Logic-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Transformation-green)
![Star Schema](https://img.shields.io/badge/Data%20Modeling-Star%20Schema-purple)

## 📊 Project Overview

An advanced Power BI dashboard designed to provide an end-to-end view of supply chain performance. The solution analyzes sales, profitability, customer behavior, shipping efficiency, delivery performance, and operational risks through interactive dashboards and business-focused KPIs.

The project transforms raw transactional data into a structured analytical solution using data cleaning, dimensional modeling, Power Query, and DAX.

## 🎯 Business Problem

Supply chain teams need clear visibility into commercial and operational performance to identify trends, monitor key performance indicators, and detect areas requiring attention.

The objective of this project was to build a centralized Supply Chain Control Tower that enables users to analyze sales and profitability, understand customer behavior, monitor shipping and delivery performance, and investigate operational exceptions through interactive Power BI dashboards.

## 💡 Project Objective

The objective of this project was to develop an interactive analytics solution that provides management with a consolidated view of commercial and operational performance while enabling users to identify trends, monitor KPIs, and investigate areas requiring attention.

## 🛠️ Tools & Technologies

* **Power BI** — Dashboard development and data visualization
* **Power Query** — Data cleaning and transformation
* **DAX** — Business calculations, KPIs, and analytical logic
* **Data Modeling** — Star-schema design and relationships
* **Excel/CSV Data** — Source transactional data

## 🧹 Data Preparation

The raw transactional data was prepared and transformed using Power Query before being used for analysis.

Key data preparation steps included:

* Cleaned and transformed the raw dataset
* Handled missing and inconsistent values
* Corrected data types across columns
* Standardized country and state names
* Created mapping tables to normalize inconsistent geographical values
* Removed unnecessary columns
* Renamed columns for better readability and consistency
* Prepared separate fact and dimension tables for analytical modeling
* Validated the transformed data before building the Power BI model

## 🏗️ Data Model

A **star-schema data model** was developed to create a structured and scalable foundation for analysis.

The model consists of a central **Fact Order Lines** table connected to supporting dimension tables:

* **Fact_OrderLines** — Transaction-level order and sales information
* **Dim_Customer** — Customer attributes and customer analysis
* **Dim_Product** — Product and product-category information
* **Dim_Geography** — Geographic information
* **Dim_Shipping** — Shipping and delivery attributes
* **Dim_Date** — Date, year, quarter, month, and time-based analysis

This dimensional structure helps maintain clear relationships between transactional data and descriptive attributes while supporting efficient filtering, aggregation, and analytical calculations in Power BI.

## 🧮 DAX & Business Logic

DAX was used to develop business-focused measures for evaluating commercial, customer, and supply chain performance.

### Key DAX Measures

* Total Sales
* Total Orders
* Total Customers
* Total Profit
* Profit Margin %
* Average Order Value
* Average Sales per Customer
* On-Time Delivery %
* Late Delivery %
* Cancellation Rate %
* Shipping Efficiency %
* Average Delivery Delay
* New Customers
* Repeat Customers
* New Customer Sales
* Repeat Customer Sales
* Sales Growth %
* Customer Growth %

Advanced DAX logic was used to develop KPI calculations, customer behavior analysis, growth metrics, delivery performance indicators, and time-based analysis.

The measures were designed to respond dynamically to report filters and slicers, allowing users to analyze performance across different periods, customers, products, locations, and operational dimensions.

## 📊 Key KPIs

The dashboard uses business-focused KPIs to monitor commercial performance, customer behavior, and supply chain operations.

### Commercial Performance

* Total Sales
* Total Orders
* Total Profit
* Profit Margin %
* Average Order Value

### Customer Performance

* Total Customers
* New Customers
* Repeat Customers
* New Customer Sales
* Repeat Customer Sales
* Average Sales per Customer

### Supply Chain Performance

## 📈 Dashboard Pages

The dashboard is organized into six analytical pages, each focused on a specific area of supply chain performance.

### 1. Executive Overview

Provides a consolidated view of key commercial and operational KPIs, enabling users to quickly assess overall business performance.

### 2. Supply Chain Operations

Focuses on shipping, delivery, and operational performance to help identify delays, inefficiencies, and areas requiring attention.

### 3. Geographic Intelligence

Provides geographic analysis of business and supply chain performance across different locations.

### 4. Customer & Sales Analytics

Analyzes customer behavior, sales performance, new versus repeat customers, and customer contribution to revenue.

### 5. Product Performance

Evaluates product-level sales, quantity, profitability, and performance patterns to identify important product trends.

### 6. Risk & Exceptions

Highlights operational exceptions and performance risks such as late deliveries, cancellations, and other areas requiring management attention.

* On-Time Delivery %
* Late Delivery %
* Late Shipments
* Average Delivery Delay
* Shipping Efficiency %
* Cancellation Rate %

## 💡 Key Business Insights

The dashboard enables analysis of the following business areas:

* **Sales Performance** — Monitor sales trends and identify periods of stronger or weaker performance.
* **Customer Behavior** — Compare new and repeat customers and understand their contribution to sales.
* **Delivery Performance** — Evaluate on-time and late delivery patterns to identify service-level issues.
* **Shipping Efficiency** — Compare scheduled and actual shipping performance to identify delivery delays.
* **Product Performance** — Analyze product-level sales, quantity, and profitability to identify performance differences.
* **Geographic Performance** — Compare performance across locations and identify areas requiring further investigation.
* **Operational Risks** — Monitor cancellations, late shipments, and other exceptions that may affect supply chain performance.

> **Note:** Specific numerical insights and observations will be added after validating the final dashboard results.

## 🎯 Business Value

The Supply Chain Control Tower provides a centralized view of commercial and operational performance, helping decision-makers:

* Monitor sales and profitability trends
* Track customer acquisition and retention patterns
* Evaluate delivery and shipping performance
* Identify operational delays and exceptions
* Analyze product and geographic performance
* Focus attention on areas requiring further investigation

The solution demonstrates how transactional data can be transformed into an interactive business intelligence solution that supports data-driven decision-making.

## 📁 Project Files

The repository contains the resources used to present and document the Supply Chain Control Tower project.

* **Power BI Dashboard** — Interactive `.pbix` report
* **Dashboard Screenshots** — Selected views of the completed dashboard
* **Project Documentation** — Business problem, methodology, KPIs, and insights

> The repository is intended to provide a clear overview of the project while keeping the analytical workflow and supporting resources organized.

## 🖥️ Dashboard Preview

### Executive Overview

![Executive Overview](01-executive-overview.png)

### Supply Chain Operations

![Supply Chain Operations](02-supply-chain-operations.png)

### Geographic Intelligence

![Geographic Intelligence](03-geographic-intelligence.png)

### Customer & Sales Analytics

![Customer & Sales Analytics](04-customer-sales-analytics.png)

### Product Performance

![Product Performance](05-product-performance.png)

### Risk & Exceptions

![Risk & Exceptions](06-risk-exceptions.png)
