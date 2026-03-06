# Grocery Inventory Analytics Dashboard

## Project Overview

This project analyzes **inventory performance, stock levels, and reorder risks** for a grocery retail environment. The objective is to monitor stock availability, identify products approaching reorder levels, and provide operational insights for inventory management.

The solution combines **Excel for data preparation, SQL for data aggregation, and Power BI for interactive visualization** to transform raw inventory data into actionable insights.

---

## Business Problem

Retail businesses must balance inventory levels to:

* prevent stockouts
* avoid excess inventory
* maintain efficient supply chain operations

Without proper inventory visibility, businesses may experience:

* lost revenue due to unavailable products
* inefficient stock management
* delayed replenishment decisions

This dashboard provides a **centralized view of inventory performance and product-level stock monitoring**.

---

## Objectives

The analysis focuses on answering the following questions:

* Which products are **below the reorder level**?
* How does **inventory fluctuate over time**?
* Which product categories hold the **largest stock quantities**?
* What percentage of products are **active, discontinued, or backordered**?
* Which SKUs require **immediate replenishment**?

---

## Data Pipeline

### 1. Data Preparation (Excel)

The raw dataset was prepared in Excel through:

* data cleaning
* formatting product attributes
* standardizing category fields
* handling missing values
* structuring tables for SQL analysis

---

### 2. Data Processing (SQL)

SQL was used to prepare analytical datasets and compute aggregated metrics.

Key operations included:

* joining product and inventory tables
* calculating stock quantities by category
* identifying reorder risk
* generating monthly inventory summaries

Example operations included:

```
JOIN product tables with inventory tables
GROUP BY product category
SUM stock quantities
calculate reorder risk indicators
```

---

### 3. Visualization Layer (Power BI)

Power BI was used to create an **interactive dashboard for inventory monitoring**.

The dashboard includes:

* KPI summary metrics
* inventory trend analysis
* category-level stock comparison
* product lifecycle monitoring
* SKU-level reorder alerts

---

## Dashboard Features

### KPI Metrics

The dashboard tracks key inventory indicators:

* Total Stock Quantity
* Total Stock Value
* Products Below Reorder Level
* Average Inventory Turnover Ratio

---

### Inventory Trend Analysis

A time-series visualization shows how stock levels change across months and compares them with reorder thresholds.

This helps identify **seasonal demand patterns and inventory pressure periods**.

---

### Category-Level Inventory Monitoring

Inventory quantities are analyzed across product categories such as:

* Fruits & Vegetables
* Dairy
* Bakery
* Seafood
* Oils & Fats
* Beverages

This allows identification of categories with **high inventory turnover or stock accumulation**.

---

### Product Lifecycle Status

Products are categorized into lifecycle states:

* Active
* Backordered
* Discontinued

The dashboard visualizes their distribution to support **inventory planning and product management decisions**.

---

### SKU-Level Reorder Monitoring

A detailed product table highlights SKUs that:

* fall below reorder thresholds
* require replenishment
* remain within safe stock levels

This provides operational visibility for inventory control.

---

## Key Insights

Some example insights derived from the analysis include:

* Certain bakery SKUs consistently approach reorder levels.
* Fresh produce categories show higher inventory turnover.
* A small percentage of products account for most reorder alerts.
* Stock fluctuations indicate seasonal demand variation.

---

## Tools & Technologies

Power BI

SQL

Excel

Data modeling and visualization techniques

---

## Project Skills Demonstrated

This project demonstrates:

* end-to-end analytics workflow
* SQL-based data aggregation
* data preparation and cleaning
* interactive BI dashboard development
* operational KPI monitoring
* business-oriented data analysis


* **Dashboard Screenshots**
* **Project Architecture**

It makes your GitHub look **10x more professional**.
