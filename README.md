<!-- BLUE GRADIENT BANNER -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D47A1,50:1976D2,100:64B5F6&height=220&section=header&text=E-Commerce%20Sales%20%26%20Customer%20Analytics&fontSize=32&fontColor=FFFFFF&fontAlignY=40&desc=MySQL%20Data%20Analysis%20Project&descAlignY=60&descSize=18" width="100%" alt="Blue gradient E-Commerce Sales and Customer Analytics banner" />
</p>

<h1 align="center">E-Commerce Sales & Customer Analytics</h1>

<p align="center">
  A beginner-to-intermediate MySQL data analysis project focused on understanding customer behaviour, product performance, sales activity, payments, reviews, revenue, and customer retention.
</p>

---

## Project Overview

This project uses MySQL to analyze an e-commerce business and turn transactional data into useful business insights.

The database contains information about customers, products, orders, order items, payments, reviews, revenue, and customer retention. The analysis helps explain how customers purchase products, which products perform well, how much revenue is generated, and how customers interact with the business.

The project was created using the SQL concepts covered in my learning notes. It focuses on practical SQL querying and business analysis rather than advanced SQL techniques.

## Project Objectives

- Analyze total sales and order activity.
- Identify high-value customers.
- Understand customer purchasing behaviour.
- Examine product prices, costs, stock, and performance.
- Analyze payment methods and payment status.
- Review customer ratings and product feedback.
- Calculate revenue, cost, and profit using stored transaction data.
- Examine customer order frequency and retention information.
- Practice using SQL to answer real business questions.

## Database Tables

| Table | Description |
|---|---|
| `Customers` | Stores customer details such as name, gender, age, location, email, and registration date. |
| `Products` | Stores product names, categories, prices, costs, and stock quantities. |
| `Orders` | Stores customer orders, order dates, order status, and payment methods. |
| `Order_Items` | Stores the products included in each order, quantities, and unit prices. |
| `Payments` | Stores payment dates, payment methods, payment status, and payment amounts. |
| `Reviews` | Stores customer ratings and review dates for products. |
| `Revenue` | Stores gross revenue, total cost, and profit for each order. |
| `Retention` | Stores customer order activity and customer status information. |

## SQL Concepts Used

- `CREATE DATABASE`
- `CREATE TABLE`
- `PRIMARY KEY`
- `FOREIGN KEY`
- `AUTO_INCREMENT`
- `NOT NULL`
- `UNIQUE`
- `DEFAULT`
- `CHECK`
- `INSERT INTO`
- `SELECT`
- `UPDATE`
- `DELETE`
- `INNER JOIN`
- `LEFT JOIN`
- `RIGHT JOIN`
- `WHERE`
- `AND`, `OR`, and `NOT`
- `LIKE` and wildcard searches
- `ORDER BY`
- `LIMIT`
- `GROUP BY`
- `ROLLUP`
- `COUNT()`
- `SUM()`
- `AVG()`
- `MIN()`
- `MAX()`
- `CONCAT()`
- Subqueries
- Views
- Indexes
- `UNION`
- `UNION ALL`
- Self joins
- `UPDATE` with joins

## Business Questions Answered

1. How many customers are in the database?
2. How many products are available?
3. How many orders have been placed?
4. What is the total sales value?
5. Which customers have placed the most orders?
6. Which customers have generated the highest sales value?
7. Which products are the most expensive?
8. Which product categories are available?
9. What is the average product price?
10. Which products have low stock quantities?
11. What payment methods are used most often?
12. How many payments are completed, pending, or failed?
13. What is the average customer review rating?
14. Which products have the highest ratings?
15. What is the total revenue and profit?
16. Which orders generated the highest revenue?
17. How many customers are new, active, or inactive based on the retention data?
18. What customer and product information can be combined using joins?

## Project Focus

The main focus of this project is to demonstrate how MySQL can be used to:

- Organize business data into related tables.
- Connect tables using primary and foreign keys.
- Retrieve useful information using SQL queries.
- Summarize data with aggregate functions.
- Compare customers, products, orders, and revenue.
- Create reusable views for analysis.
- Support business decision-making with data.

## Tools Used

- **MySQL**
- **SQL**
- **phpMyAdmin / MySQL Workbench**
- **GitHub**

## Project Level

**Beginner to Intermediate MySQL Data Analysis**

This project does not use advanced SQL features such as:

- Common Table Expressions (`CTEs`)
- `RANK()`
- `ROW_NUMBER()`
- `LAG()`
- `LEAD()`
- `PARTITION BY`
- Stored procedures
- Triggers

## Author

**Wilson Afolabi**  
Computer Science Student | Data Analyst | Project Management Enthusiast | Virtual Assistant
