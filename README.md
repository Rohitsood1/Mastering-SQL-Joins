# Mastering-SQL-Joins
A beginner-friendly SQL Joins tutorial covering INNER JOIN, LEFT JOIN, RIGHT JOIN, and FULL JOIN with syntax, explanations, practical examples, and real-world scenarios.
# SQL Joins Guide

A comprehensive beginner-friendly guide to understanding SQL Joins with examples and practical scenarios.

## 📖 Overview

SQL Joins are used to combine data from two or more tables based on a related column between them. Joins help retrieve meaningful information stored across multiple tables in relational databases.

This repository explains:

- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- FULL JOIN

with syntax, examples, and result analysis.

---

## 🔹 What is a JOIN?

A SQL JOIN clause combines rows from two or more tables based on a related column between them.

Joins allow users to:

- Retrieve data from multiple tables
- Build reports and dashboards
- Analyze relational data efficiently

---

## 📌 Types of SQL Joins

### 1. INNER JOIN

Returns only matching records from both tables.

#### Syntax

```sql
SELECT *
SELECT *
FROM table1
LEFT JOIN table2
ON table1.column_name = table2.column_name;

SELECT *
FROM table1
RIGHT JOIN table2
ON table1.column_name = table2.column_name;

SELECT *
FROM table1
FULL OUTER JOIN table2
ON table1.column_name = table2.column_name;
FROM table1
INNER JOIN table2
ON table1.column_name = table2.column_name;
