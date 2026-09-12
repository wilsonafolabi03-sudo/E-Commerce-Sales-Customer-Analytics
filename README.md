# 🛒 E-Commerce Sales & Customer Analytics

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:141E30,100:243B55&height=180&section=header&text=E-Commerce%20Sales%20Analytics&fontSize=35&fontColor=ffffff&animation=fadeIn&fontAlignY=35" alt="E-Commerce Sales Analytics banner" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=2F80ED&center=true&vCenter=true&width=700&lines=MySQL+Portfolio+Project;Customer+%26+Sales+Intelligence;Beginner-to-Intermediate+SQL+Analytics;Turning+Raw+Data+into+Business+Insights" alt="Animated typing introduction" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Database-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL badge" />
  <img src="https://img.shields.io/badge/Project-SQL%20Analytics-2F80ED?style=for-the-badge" alt="SQL Analytics badge" />
  <img src="https://img.shields.io/badge/Level-Beginner%20%2F%20Intermediate-27AE60?style=for-the-badge" alt="Skill level badge" />
  <img src="https://img.shields.io/badge/Status-Completed-16A085?style=for-the-badge" alt="Completed badge" />
</p>

---

## 📌 Project Overview

The **E-Commerce Sales & Customer Analytics** project is a MySQL database project created to demonstrate how SQL can be used to organize, manage, and analyze e-commerce data.

The project contains customer, product, order, payment, review, revenue, and retention information. It uses SQL queries to answer business questions such as:

- Which products generate the highest sales?
- Which customers place the most orders?
- What is the total revenue generated?
- Which product categories perform best?
- What payment methods are most commonly used?
- How do customer reviews affect product evaluation?
- Which customers are active or inactive based on their order activity?

The project is designed around beginner-to-intermediate SQL concepts from my course note. It does **not** use advanced SQL features such as CTEs, window functions, stored procedures, or triggers.

---

## 🎯 Project Objectives

1. Create a relational e-commerce database using MySQL.
2. Create connected tables using primary keys and foreign keys.
3. Insert a large amount of sample data into the database.
4. Practice SQL data retrieval and filtering.
5. Analyze sales, customers, products, payments, and revenue.
6. Use aggregate functions to generate business insights.
7. Create views and indexes for easier analysis and better organization.
8. Prepare a practical SQL project suitable for a portfolio or GitHub repository.

---

## 🧰 Tools and Technologies

| Tool | Purpose |
|---|---|
| MySQL | Database creation and analysis |
| MySQL Workbench / phpMyAdmin | Running SQL commands |
| SQL | Data management and analysis |
| GitHub | Project documentation and portfolio presentation |
| Markdown | Repository documentation |

---

## 🗂️ Database Structure

The database is named:

```sql
 ecommerce_analytics
```

### Main Tables

| Table | Description |
|---|---|
| `Customers` | Stores customer details and registration information |
| `Products` | Stores product names, categories, prices, costs, and stock |
| `Orders` | Stores customer orders and order status |
| `Order_Items` | Stores the products included in each order |
| `Payments` | Stores payment details and payment status |
| `Reviews` | Stores customer product ratings and review dates |
| `Revenue` | Stores gross revenue, total cost, and profit information |
| `Retention` | Stores customer order activity and customer status |

---

## 🔗 Database Relationships

```text
Customers 1 ────────────< Orders
Orders 1 ───────────────< Order_Items
Products 1 ─────────────< Order_Items
Orders 1 ───────────────< Payments
Customers 1 ────────────< Reviews
Products 1 ─────────────< Reviews
Orders 1 ───────────────< Revenue
Customers 1 ────────────< Retention
```

The database uses **primary keys** to uniquely identify records and **foreign keys** to connect related tables.

---

## 📊 Dataset Summary

The project contains at least 300 records in each major table.

| Table | Approximate Records |
|---|---:|
| Customers | 400 |
| Products | 350 |
| Orders | 800 |
| Order_Items | 1,600 |
| Payments | 800 |
| Reviews | 400 |
| Revenue | 800 |
| Retention | 400 |

> The data is synthetic and created for learning, practice, demonstration, and portfolio purposes.

---

## 🧠 SQL Concepts Used

This project uses the following SQL concepts:

- `CREATE DATABASE`
- `CREATE TABLE`
- `INSERT INTO`
- `SELECT`
- `WHERE`
- `AND`, `OR`, and `NOT`
- `LIKE` and wildcard searches
- `ORDER BY`
- `LIMIT`
- `UPDATE`
- `DELETE`
- `PRIMARY KEY`
- `FOREIGN KEY`
- `AUTO_INCREMENT`
- `NOT NULL`
- `UNIQUE`
- `DEFAULT`
- `CHECK`
- `INNER JOIN`
- `LEFT JOIN`
- `RIGHT JOIN`
- `GROUP BY`
- `ROLLUP`
- `COUNT()`
- `SUM()`
- `AVG()`
- `MIN()`
- `MAX()`
- `CONCAT()`
- Subqueries
- `UNION`
- `UNION ALL`
- Self joins
- Views
- Indexes
- `UPDATE ... JOIN`
- Basic transaction commands

### 🚫 Advanced Features Excluded

The following features were intentionally excluded so the project remains aligned with the course note:

- Common Table Expressions — CTEs
- `RANK()`
- `ROW_NUMBER()`
- `LAG()`
- `LEAD()`
- `PARTITION BY`
- Stored procedures
- Triggers
- `CASE`
- `COALESCE()`
- `NULLIF()`
- Calculated fields

---

## 📁 Repository Structure

```text
E-Commerce-Sales-Customer-Analytics/
│
├── README.md
│
├── ecommerce_sales_customer_analytics_beginner_intermediate.sql
│
├── documentation/
│   ├── project-overview.md
│   ├── business-questions.md
│   └── sql-topics-used.md
│
├── screenshots/
│   ├── database-tables.png
│   ├── customer-analysis.png
│   ├── sales-analysis.png
│   └── revenue-analysis.png
│
└── results/
    ├── customer-analysis-results.csv
    ├── product-analysis-results.csv
    └── revenue-analysis-results.csv
```

> Only the SQL script and `README.md` are required to run the project. The other folders are optional documentation and presentation materials.

---

## ▶️ How to Run the Project

### Step 1: Install MySQL

Install one of the following:

- MySQL Server and MySQL Workbench
- XAMPP with phpMyAdmin
- WAMP with phpMyAdmin

### Step 2: Open the SQL File

Open:

```text
 ecommerce_sales_customer_analytics_beginner_intermediate.sql
```

### Step 3: Run the Script

Copy the script into MySQL Workbench or phpMyAdmin and execute it.

The script will:

1. Create the database.
2. Create all tables.
3. Add primary keys.
4. Add foreign keys.
5. Insert the sample data.
6. Create indexes and views.
7. Run analysis queries.

### Step 4: Select the Database

```sql
USE ecommerce_analytics;
```

### Step 5: Check the Tables

```sql
SHOW TABLES;
```

### Step 6: Check the Number of Records

```sql
SELECT 'Customers' AS table_name, COUNT(*) AS total_records FROM Customers
UNION ALL
SELECT 'Products', COUNT(*) FROM Products
UNION ALL
SELECT 'Orders', COUNT(*) FROM Orders
UNION ALL
SELECT 'Order_Items', COUNT(*) FROM Order_Items
UNION ALL
SELECT 'Payments', COUNT(*) FROM Payments
UNION ALL
SELECT 'Reviews', COUNT(*) FROM Reviews
UNION ALL
SELECT 'Revenue', COUNT(*) FROM Revenue
UNION ALL
SELECT 'Retention', COUNT(*) FROM Retention;
```

---

## 📈 Example Business Analysis Questions

### 1. Total Number of Customers

```sql
SELECT COUNT(*) AS total_customers
FROM Customers;
```

### 2. Total Number of Orders

```sql
SELECT COUNT(*) AS total_orders
FROM Orders;
```

### 3. Total Revenue

```sql
SELECT SUM(gross_revenue) AS total_revenue
FROM Revenue;
```

### 4. Total Profit

```sql
SELECT SUM(profit) AS total_profit
FROM Revenue;
```

### 5. Average Product Price

```sql
SELECT AVG(price) AS average_product_price
FROM Products;
```

### 6. Best-Selling Products

```sql
SELECT
    p.product_name,
    SUM(oi.quantity) AS total_quantity_sold
FROM Products p
INNER JOIN Order_Items oi
    ON p.product_id = oi.product_id
GROUP BY p.product_id, p.product_name
ORDER BY total_quantity_sold DESC
LIMIT 10;
```

### 7. Revenue by Product Category

```sql
SELECT
    p.category,
    SUM(oi.quantity * oi.unit_price) AS category_sales
FROM Products p
INNER JOIN Order_Items oi
    ON p.product_id = oi.product_id
GROUP BY p.category
ORDER BY category_sales DESC;
```

### 8. Customers with the Highest Number of Orders

```sql
SELECT
    c.customer_name,
    COUNT(o.order_id) AS total_orders
FROM Customers c
INNER JOIN Orders o
    ON c.customer_id = o.customer_id
GROUP BY c.customer_id, c.customer_name
ORDER BY total_orders DESC
LIMIT 10;
```

### 9. Average Product Rating

```sql
SELECT
    p.product_name,
    AVG(r.rating) AS average_rating
FROM Products p
INNER JOIN Reviews r
    ON p.product_id = r.product_id
GROUP BY p.product_id, p.product_name
ORDER BY average_rating DESC;
```

### 10. Payment Method Usage

```sql
SELECT
    payment_method,
    COUNT(*) AS number_of_payments
FROM Payments
GROUP BY payment_method
ORDER BY number_of_payments DESC;
```

---

## 💡 Key Business Insights This Project Can Provide

This database can help an e-commerce business understand:

- Customer purchasing behavior.
- Product demand and performance.
- Revenue and profit trends.
- Popular payment methods.
- Product review performance.
- Customer order frequency.
- Stock and product category performance.
- Customers who may need retention campaigns.
- Products that may need restocking.
- Areas where business performance can improve.

---

## 🧪 Data Quality and Database Features

The project demonstrates:

- Unique customer emails.
- Required fields using `NOT NULL`.
- Automatic IDs using `AUTO_INCREMENT`.
- Data validation using `CHECK` constraints.
- Relationships using foreign keys.
- Organized tables using relational database design.
- Views for reusable analysis.
- Indexes for commonly searched fields.

---

## 🚀 Possible Future Improvements

Future versions of this project may include:

- Power BI dashboard integration.
- Excel dashboard integration.
- Tableau visualizations.
- Python data analysis using Pandas.
- More detailed customer segmentation.
- Monthly revenue reports.
- Product inventory alerts.
- Marketing campaign analysis.
- Advanced SQL analysis after learning window functions and CTEs.

---

## 👨‍💻 Author

**Wilson Afolabi**  
Computer Science Student | Data Analyst | Project Management Enthusiast | Virtual Assistant

### Areas of Interest

- Data Analysis
- SQL and Database Management
- Business Intelligence
- Project Management
- Virtual Assistance
- Data Visualization

---

## 📬 Contact and Portfolio

- GitHub: [wilsonafolabi03-sudo](https://github.com/wilsonafolabi03-sudo)
- LinkedIn: Add your LinkedIn profile link here
- Email: Add your professional email here

---

## ⭐ Project Support

If this project is useful, you can support it by:

1. Starring the repository.
2. Sharing feedback.
3. Suggesting improvements.
4. Connecting with me for collaboration opportunities.

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:243B55,100:141E30&height=120&section=footer" alt="Footer banner" />
</p>
