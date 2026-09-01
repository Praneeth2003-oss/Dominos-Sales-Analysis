# 🍕 Domino's Pizza Sales Analysis

## 📊 Project Overview

This project analyzes Domino's pizza sales data to understand overall sales performance, customer ordering patterns, popular pizza categories, pizza sizes, and sales trends over time.

The analysis was performed using **MySQL** and the results were presented through a **Tableau-style sales dashboard**.

The main goal of the project is to turn raw pizza order data into useful business insights that can help understand which pizzas, categories, and sizes perform best.

---

## 🎯 Project Objectives

- Analyze overall pizza sales performance
- Calculate important sales KPIs
- Identify the most and least popular pizzas
- Analyze sales by pizza category and size
- Understand monthly and daily order trends
- Analyze orders by day of the week
- Compare pizza categories based on revenue and quantity sold
- Identify top and bottom performing pizzas
- Create a dashboard to present the findings visually

---

## 🛠️ Tools & Technologies

- **MySQL** – Data analysis and SQL queries
- **SQL** – Data aggregation, filtering, grouping and ranking
- **Tableau** – Dashboard and data visualization
- **GitHub** – Project documentation and version control

---

## 📁 Dataset

The analysis uses a pizza sales dataset containing information related to:

- Order ID
- Order Date
- Order Time
- Pizza Name
- Pizza Category
- Pizza Size
- Quantity
- Total Price

The SQL script creates and uses a database named `pizza_sales` and performs the analysis on the `PIZZA_SALES` table.

---

## 📌 Key Performance Indicators

The dashboard focuses on the following KPIs:

| KPI | Description |
|---|---|
| **Total Revenue** | Total sales revenue generated from pizza orders |
| **Total Orders** | Number of unique orders |
| **Total Pizzas Sold** | Total quantity of pizzas sold |
| **Average Pizza / Order** | Average number of pizzas purchased per order |
| **Average Order Value** | Average revenue generated per order |

The KPI calculations are based on the SQL analysis, including total revenue, distinct orders, total quantity, average order value, and average pizzas per order. fileciteturn0file0L15-L30

---

## 📈 Dashboard

The dashboard provides an overview of pizza sales performance using different visualizations.

### Dashboard Includes

- Monthly Order Trend
- Daily Order Trend
- Total Pizzas Sold by Pizza Category
- Pizza Size Sales %
- Pizza Category Sales %
- Total Revenue
- Total Orders
- Total Pizzas Sold
- Average Pizza per Order
- Average Order Value

### Dashboard Preview

![Pizza Sales Dashboard](pizza_sales_tableau_sample_dashboard.jpg)

---

## 🔍 SQL Analysis

Several SQL queries were written to analyze different aspects of the business.

### 1. Overall Sales Performance

The analysis calculates:

- Total revenue
- Total orders
- Total pizzas sold
- Average order value
- Average pizzas per order

For example, Average Order Value is calculated by dividing total revenue by the number of distinct orders. fileciteturn0file0L19-L30

---

### 2. Orders by Day of Week

The project analyzes the number of orders placed on each day of the week.

This helps identify which days have higher customer demand. fileciteturn0file0L37-L40

---

### 3. Monthly Order Analysis

Orders are grouped by month to understand changes in order volume throughout the year. fileciteturn0file0L42-L45

---

### 4. Sales by Hour

Order activity is also analyzed by hour along with pizza category.

This can help identify peak ordering periods during the day. fileciteturn0file0L47-L54

---

### 5. Pizza Category Analysis

The project compares pizza categories based on:

- Total sales
- Percentage contribution to total sales
- Total quantity sold

The categories are grouped and ranked to identify stronger-performing segments. fileciteturn0file0L56-L65 fileciteturn0file1L130-L134

---

### 6. Pizza Size Analysis

Pizza sizes are analyzed based on their contribution to total sales.

This helps understand which pizza sizes are preferred by customers. fileciteturn0file0L67-L78

---

### 7. Top & Bottom Performing Pizzas

The project identifies the best and worst performing pizzas based on different metrics.

#### Top 5

- Top 5 pizzas by revenue
- Top 5 pizzas by quantity sold
- Top 5 pizzas by number of orders

#### Bottom 5

- Bottom 5 pizzas by revenue
- Bottom 5 pizzas by quantity sold
- Bottom 5 pizzas by number of orders

These queries use `GROUP BY`, `SUM()`, `COUNT()`, `ORDER BY`, and `LIMIT` to rank pizza products. fileciteturn0file1L94-L116

---

## 📊 Key Dashboard Metrics

Based on the dashboard:

| Metric | Value |
|---|---:|
| Total Revenue | **$817.9K** |
| Total Orders | **21.4K** |
| Total Pizzas Sold | **49.6K** |
| Average Pizza / Order | **2.3** |
| Average Order Value | **$38.3** |

### Category Performance

The dashboard shows that **Classic pizzas** have the highest number of pizzas sold among the four categories shown.

| Category | Pizzas Sold |
|---|---:|
| Classic | 14.89K |
| Supreme | 11.99K |
| Veggie | 11.65K |
| Chicken | 11.05K |

---

## 💡 Business Insights

Some of the main observations from the analysis are:

- The business generated approximately **$817.9K in total revenue**.
- More than **21K orders** were placed.
- Around **49.6K pizzas** were sold.
- Customers purchased an average of approximately **2.3 pizzas per order**.
- The **Classic** category has the highest pizza sales volume.
- **Large and Medium pizzas** account for a significant portion of sales.
- Order volume varies across different months.
- Friday shows one of the highest daily order volumes in the dashboard.
- Ranking pizzas by revenue and quantity can help identify products that contribute most to overall performance.

---
