# SQL for Data Analysis 🚀

## Overview
This project contains SQL queries for basic data analysis tasks using a sample Ecommerce SQL dataset.  
I have used MySQL (you can mention SQLite/PostgreSQL if you use them).

## Files
- `task3_queries.sql`: Contains all the SQL queries.
- `screenshots/`: Folder containing output screenshots for each query.

## Key SQL Concepts Used
- SELECT, WHERE, ORDER BY, GROUP BY
- JOINS (INNER JOIN, LEFT JOIN, RIGHT JOIN)
- Subqueries
- Aggregate functions (SUM, AVG)
- Creating Views
- Query Optimization using Indexes

## Sample Interview Questions and Answers

### 1. Difference between WHERE and HAVING
- **WHERE** is used to filter rows before grouping.
- **HAVING** is used to filter groups after aggregation.

### 2. Types of Joins
- **INNER JOIN**: returns matching rows from both tables.
- **LEFT JOIN**: returns all rows from the left table, matched rows from the right.
- **RIGHT JOIN**: returns all rows from the right table, matched rows from the left.

### 3. How to calculate average revenue per user
```sql
SELECT AVG(amount) FROM orders;
