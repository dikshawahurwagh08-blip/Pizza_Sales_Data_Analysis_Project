# 🍕 Pizza Sales Analysis Using SQL

## 📌 Project Overview

This project focuses on analyzing pizza sales data using SQL. The objective is to extract meaningful business insights from sales transactions, customer ordering patterns, revenue generation, and product performance.

The project demonstrates the use of SQL concepts such as:

- Joins
- Aggregate Functions
- Group By
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions
- Ranking Functions

---

## 🎯 Objectives

- Analyze overall sales performance.
- Identify best-selling pizzas.
- Calculate total revenue.
- Understand customer ordering behavior.
- Determine category-wise and size-wise sales distribution.
- Find top revenue-generating pizzas.
- Generate business insights for decision-making.

---

## 🛠️ Technologies Used

- SQL (MySQL)
- MySQL Workbench
- CSV Dataset

---

## 📂 Dataset Information

The project uses four datasets:

### 1. Orders Table
Contains order details.

| Column |
|----------|
| order_id |
| order_date |
| order_time |

### 2. Order Details Table
Contains pizza order quantities.

| Column |
|----------|
| order_details_id |
| order_id |
| pizza_id |
| quantity |

### 3. Pizzas Table
Contains pizza size and pricing information.

| Column |
|----------|
| pizza_id |
| pizza_type_id |
| size |
| price |

### 4. Pizza Types Table
Contains pizza category and name.

| Column |
|----------|
| pizza_type_id |
| name |
| category |
| ingredients |

---

## 📊 Business Questions Solved

### Basic Analysis

1. Retrieve the total number of orders placed.
2. Calculate total revenue generated from pizza sales.
3. Identify the highest-priced pizza.
4. Identify the most common pizza size ordered.
5. List the top 5 most ordered pizza types.

### Intermediate Analysis

6. Find total quantity ordered by pizza category.
7. Determine distribution of orders by hour.
8. Category-wise distribution of pizzas.
9. Calculate average pizzas ordered per day.
10. Find top 3 pizza types based on revenue.

### Advanced Analysis

11. Calculate percentage contribution of each pizza category to revenue.
12. Analyze cumulative revenue generated over time.
13. Determine top 3 revenue-generating pizzas within each category.

---

## 📈 Key Insights

### Total Orders

- 21,350 orders were placed.

### Total Revenue

- Revenue generated: $817,860.05

### Highest Priced Pizza

- The Greek Pizza

### Most Ordered Pizza Size

- Large (L)

### Best Selling Pizza

- The Classic Deluxe Pizza

### Peak Sales Hours

- Lunch Time
- Evening Hours

### Highest Revenue Categories

- Classic
- Supreme
- Chicken

---

## 🔥 SQL Concepts Used

### Aggregate Functions

```sql
COUNT()
SUM()
AVG()
MAX()
MIN()
