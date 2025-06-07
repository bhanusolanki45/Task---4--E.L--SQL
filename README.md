# Task---4--E.L--SQL

## Overview

This repository contains the solution for Task 3 of the Elevate Labs Internship, focusing on SQL-based data analysis using a custom ecommerce database in PostgreSQL.
The task involved creating a database, populating it with sample data, and writing SQL queries to extract and analyze data, meeting requirements such as using SELECT, WHERE, ORDER BY, GROUP BY, JOINS, subqueries, aggregate functions, views, and indexes.

Key Learnings

* Database Schema Design: Designed a relational ecommerce database with appropriate keys, learning to model real-world business data.
  
* Core SQL Skills: Mastered SELECT, WHERE, ORDER BY, and GROUP BY for filtering, sorting, and aggregating data.
  
* Joins: Used INNER JOIN and LEFT JOIN to combine data, understanding their differences in handling records.

* Subqueries: Wrote nested queries for complex filtering, such as identifying high-value customers.

* Aggregate Functions: Applied SUM and AVG to derive business metrics like total sales and average order value.

* Views: Created reusable views to simplify analysis, enhancing query efficiency.

* Indexes: Learned to optimize queries with indexes, improving performance for frequent filters.


## Queries

# The ecommerce_Database.sql file includes 15 queries:

1. Select all customers, ordered by name.

2. Select products with low stock (stock_quantity < 10).

3. Count orders per customer using GROUP BY.

4. List orders with customer names using INNER JOIN.

5. List all customers and their orders using LEFT JOIN.

6. List order items with product names using INNER JOIN.

7. Find customers with orders > $500 using a subquery.

8. Find products that have been ordered using a subquery.

9. Calculate total sales using SUM.

10. Calculate average order value using AVG.

11. Calculate total quantity sold per product.

12. Create a view for customer orders (Customer_Orders).

13. Create a view for product sales (Product_Sales).

14. Create an index on customer_id in Orders.
