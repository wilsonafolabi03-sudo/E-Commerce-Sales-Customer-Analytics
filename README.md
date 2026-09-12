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

The project was created using the SQL concepts covered in my learning notes, with a focus on practical SQL querying and business analysis.

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

## Real-Life Business Scenario: E-Commerce Sales Intelligence

### Scenario

An online retail company wants to understand its sales performance and customer behaviour using the data collected from its day-to-day operations. Management needs answers to important questions about customers, products, orders, payments, reviews, revenue, profit, and retention.

As a junior data analyst, you have been asked to use MySQL to analyze the company's database and provide insights that can support better business decisions.

### Business Analysis Questions

1. Which customers are placing the most orders?
2. Which customers generate the highest sales value for the company?
3. Which products and product categories perform best?
4. Which products have low stock and may require restocking?
5. Which payment methods are most commonly used by customers?
6. What is the current payment status of customer orders?
7. Which products receive the highest customer ratings?
8. What is the company's total revenue, cost, and profit?
9. Which orders contribute the most to revenue?
10. How frequently are customers purchasing from the business?
11. What does the customer retention data reveal about customer activity?
12. How can information from different tables be combined to give management a clearer view of the business?

### Business Goal

The goal is to turn raw e-commerce transaction data into practical information that management can use to understand sales performance, improve customer relationships, manage products and inventory, and make better business decisions.

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

## Author

**Wilson Afolabi**  
Computer Science Student | Data Analyst | Project Management Enthusiast | Virtual Assistant
