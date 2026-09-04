# 📊 Sales Analysis Dashboard – Power BI

A professional **Sales Analysis Dashboard** built using Microsoft Power BI to analyze sales performance, products, customers, and time-based trends through an interactive report.

## 📌 Dashboard Overview

This Power BI project provides an interactive view of sales data and helps users understand:

- Overall sales performance
- Sales trends over time
- Product and category performance
- Customer contribution
- Order quantity and sales distribution
- Top and least-selling products
- Customer Recency, Frequency, and Monetary (RFM) analysis

## 📑 Dashboard Pages

| Page | Description |
|------|-------------|
| 🏠 **Index** | Dashboard landing and navigation page |
| 📊 **Overview** | Overall sales performance and key business KPIs |
| 📈 **Sales** | Sales trends by day, month, and week |
| 📦 **Product** | Product and category performance analysis |
| 👥 **Customer** | Customer performance and RFM analysis |

## 🔑 Key KPIs

The dashboard contains important business metrics such as:

- 💰 Total Sales
- 📦 Total Quantity
- 🧾 Total Orders
- 👥 Total Customers
- 💵 Average Order Value
- 🛍️ Total Products
- 🗂️ Total Categories
- 🏆 Best Selling Product
- 📉 Least Selling Product
- 👑 Top Customer
- 🔄 Customer Frequency
- 📅 Customer Recency
- 💰 Customer Monetary Value

## 📈 Visualizations

The dashboard uses different Power BI visuals:

- KPI Cards
- Line Charts
- Bar Charts
- Column Charts
- Donut Charts
- Tables
- Slicers
- Interactive Filters

## 📊 Overview Page

The Overview page provides a high-level summary of the business.

### Main Analysis

- Total Sales
- Total Quantity
- Total Orders
- Total Customers
- Average Order Value
- Sales trend over time
- Sales by product category
- Sales by product

## 📈 Sales Analysis

The Sales page focuses on sales performance over time.

### Analysis Includes

- Daily Sales Trend
- Monthly Sales Trend
- Weekly Sales Performance
- Year-wise Sales
- Month-wise Sales
- Product Category Analysis
- Customer Analysis

## 📦 Product Analysis

The Product page analyzes product performance.

### Analysis Includes

- Total Products
- Total Categories
- Total Sales
- Best Selling Product
- Least Selling Product
- Quantity by Product
- Quantity by Category
- Product Performance

## 👥 Customer Analysis

The Customer page focuses on customer performance.

### Analysis Includes

- Total Customers
- Average Order Value
- Top Customer
- Quantity Purchased
- Sales by Category
- Customer-wise Performance
- RFM Analysis

### RFM Analysis

**RFM** stands for:

- **Recency** – How recently the customer purchased
- **Frequency** – How frequently the customer purchases
- **Monetary** – How much the customer spends

RFM analysis helps identify valuable and active customers.

## 🎛️ Interactive Filters

The dashboard contains interactive slicers and filters:

- 📅 Year
- 📆 Month
- 🗂️ Product Category
- 👤 Customer Name

Users can select different values to dynamically analyze the dashboard.

## 🗂️ Data Model

The Power BI project contains:

### Table1

Main sales/business data table.

Example fields:

- Bill No
- Bill Date
- Product Name
- Product Category
- Customer Name
- Quantity
- Amount
- Year Week

### DateTable

A dedicated date table used for:

- Date analysis
- Year analysis
- Month analysis
- Week analysis
- Time intelligence

## 🧮 DAX & Analysis

The project uses Power BI DAX and data modeling concepts such as:

- `SUM()`
- `AVERAGE()`
- `COUNT()`
- `DISTINCTCOUNT()`
- Ranking
- Time Intelligence
- Customer Analysis
- RFM Analysis

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Data Cleaning
- Data Visualization
- Excel

## 🚀 How to Use

1. Install **Microsoft Power BI Desktop**.
2. Download the `.pbix` file.
3. Open the Power BI project.
4. Refresh the data if required.
5. Use the dashboard navigation.
6. Apply filters and slicers.
7. Explore sales, product, and customer insights.

## 📁 Project Structure

```text
Sales-Analysis-PowerBI/
│
├── README.md
├── Sales Dashboard.pbix
└── Dataset.xlsx
