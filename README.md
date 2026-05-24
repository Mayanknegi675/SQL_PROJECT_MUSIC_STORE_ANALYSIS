# Music Store SQL Project

## Overview

This project contains SQL queries designed to analyze a Music Store database using PostgreSQL. The project focuses on solving real-world business problems using SQL concepts such as:

* Joins
* Aggregate Functions
* GROUP BY
* ORDER BY
* Subqueries
* Common Table Expressions (CTEs)
* Filtering and Sorting
* Business Analysis Queries

The project is divided into three difficulty levels:

1. Easy Queries
2. Moderate Queries
3. Advanced Queries

---

# Database Used

The project uses a Music Store relational database containing tables related to:

* Customers
* Employees
* Invoices
* Invoice Lines
* Tracks
* Albums
* Artists
* Genres

---

# Project Objectives

The main objective of this project is to practice and demonstrate SQL skills commonly used in:

* Data Analyst Interviews
* Business Intelligence
* Reporting and Analytics
* Database Query Optimization

---

# SQL Concepts Covered

## Basic SQL

* SELECT
* WHERE
* ORDER BY
* LIMIT
* DISTINCT

## Aggregate Functions

* COUNT()
* SUM()
* AVG()
* MAX()

## Joins

* INNER JOIN
* Multiple Table Joins

## Advanced SQL

* Subqueries
* CTEs (WITH Clause)
* Nested Queries
* Analytical Business Questions

---

# Question Categories

## Easy Level

Examples:

* Find the senior-most employee
* Find countries with the highest number of invoices
* Find top invoice totals
* Identify the best customer

## Moderate Level

Examples:

* Find all Rock music listeners
* Identify top Rock artists
* Find tracks longer than average song length

## Advanced Level

Examples:

* Customer spending by artist
* Best-selling artists
* Revenue analysis using invoice data

---

# Tools Used

* PostgreSQL
* pgAdmin 4
* SQL Query Tool

---

# File Structure

```text
Music_Store_Project/
│
├── Music_Store_Query.sql
├── README.md
└── Dataset Files
```

---

# How to Run the Project

## Step 1: Open PostgreSQL

Open PostgreSQL and connect to your database server.

## Step 2: Open pgAdmin 4

Launch pgAdmin 4 and connect to the database.

## Step 3: Create Database

Create a new database for the project.

## Step 4: Import Dataset

Import the Music Store dataset tables into PostgreSQL.

## Step 5: Open Query Tool

Open the Query Tool in pgAdmin.

## Step 6: Run Queries

Open the `Music_Store_Query.sql` file and execute queries one by one.

---

# Sample Query

```sql
SELECT billing_city, SUM(total) AS invoice_total
FROM invoice
GROUP BY billing_city
ORDER BY invoice_total DESC
LIMIT 1;
```

---

# Learning Outcomes

By completing this project, you will learn:

* Writing efficient SQL queries
* Solving business problems using data
* Working with relational databases
* Performing customer and sales analysis
* Using advanced SQL concepts in real-world scenarios

---

# Future Improvements

Possible future enhancements:

* Add SQL Window Functions
* Create Power BI Dashboard
* Build Tableau Visualizations
* Optimize complex queries
* Add stored procedures and views

---

# Author

Mayank Negi

---

# Conclusion

This project is a complete hands-on SQL practice project for aspiring Data Analysts and Business Analysts. It helps strengthen SQL fundamentals as well as advanced querying skills using a real-world Musi
