This course is extremely good, but the biggest mistake most learners make is trying to finish 30 hours of SQL without enough practice.

For Data Analyst, Data Engineer, or Data Scientist roles, I would recommend a **70% practice, 30% video** approach.

---

# SQL Mastery Roadmap (Structured Version)

## 📚 Phase 1: SQL Foundations (Week 1)

### Session 1 (Day 1)

**Video**

* 00:00 Intro
* 07:38 Introduction to SQL
* 22:33 Setup Your Environment
* 34:01 Query Data (SELECT)

### Learn

* What SQL is
* Databases vs Tables
* SELECT
* DISTINCT
* LIMIT/TOP
* ORDER BY

### Practice (45-60 min)

**SQLBolt**

* Lessons 1–6

**LeetCode**

* Recyclable and Low Fat Products
* Customer Who Visited but Did Not Make Any Transactions
* Big Countries

### Notes

Create your own examples:

```sql
SELECT *
FROM employees;

SELECT name, salary
FROM employees
ORDER BY salary DESC;
```

---

### Session 2 (Day 2)

**Video**

* 01:32:31 DDL Commands
* 01:43:44 DML Commands

### Learn

DDL

* CREATE
* ALTER
* DROP
* TRUNCATE

DML

* INSERT
* UPDATE
* DELETE

### Practice

SQLBolt Lessons 7–9

Create:

```sql
CREATE TABLE students(
    id INT,
    name VARCHAR(50)
);

INSERT INTO students
VALUES (1,'Shimu');
```

Build 2-3 tables manually.

---

# 📚 Phase 2: Filtering & Querying (Week 2)

### Session 3

**Video**

* 02:08:03 Filtering Data

### Learn

* WHERE
* AND
* OR
* NOT
* BETWEEN
* IN
* LIKE
* Wildcards

### Practice

SQLBolt Lessons 10–13

LeetCode:

* Employees Earning More Than Their Managers
* Find Customer Referee

### Challenge

```sql
Find employees
whose salary > 50000
and department = 'IT'
```

---

# 📚 Phase 3: Joins (Week 2)

### Session 4

**Video**

* 02:47:57 SQL Joins (Basics)

### Learn

* INNER JOIN
* LEFT JOIN
* RIGHT JOIN
* FULL JOIN

### Practice

SQLZoo JOIN Section

Draw join diagrams by hand.

### Challenge

```sql
customers
orders

Show customer name and order amount
```

---

### Session 5

**Video**

* 03:27:29 SQL Joins (Advanced)

### Learn

* Self Join
* Cross Join
* Multiple Table Join

### Practice

LeetCode

* Replace Employee ID With Unique Identifier
* Product Sales Analysis I

---

# 📚 Phase 4: Functions (Week 3)

### Session 6

**Video**

* 04:02:09 Set Operators
* 04:47:41 SQL Functions
* 04:52:58 String Functions

### Learn

* UNION
* UNION ALL
* CONCAT
* UPPER
* LOWER
* SUBSTRING
* LENGTH

### Practice

SQLBolt Review Exercises

### Mini Project

Clean messy names:

```sql
john doe
JANE DOE
```

Convert to standard format.

---

### Session 7

**Video**

* 05:18:44 Numeric Functions
* 05:22:48 Date Functions

### Learn

* ROUND
* CEIL
* FLOOR
* DATEADD
* DATEDIFF
* NOW

### Practice

20 custom queries.

---

### Session 8

**Video**

* 06:59:06 NULL Functions
* 08:07:50 CASE Statement

### Learn

* COALESCE
* ISNULL
* CASE

### Practice

```sql
CASE
 WHEN salary > 100000 THEN 'High'
 WHEN salary > 50000 THEN 'Medium'
 ELSE 'Low'
END
```

---

# 📚 Phase 5: Aggregation (Week 3)

### Session 9

**Video**

* 08:43:36 Aggregate Functions

### Learn

* COUNT
* SUM
* AVG
* MIN
* MAX
* GROUP BY
* HAVING

### Practice

LeetCode:

* Not Boring Movies
* Average Selling Price

### Challenge

Find:

* Highest salary per department
* Average sales per month

---

# 📚 Phase 6: Window Functions (Week 4)

### Session 10

**Video**

* 08:50:11 Window Functions Basics

### Learn

```sql
OVER()
PARTITION BY
```

### Practice

Create running totals.

---

### Session 11

**Video**

* 09:47:00 Window Aggregate
* 10:53:09 Window Ranking

### Learn

```sql
ROW_NUMBER()
RANK()
DENSE_RANK()
```

### Practice

LeetCode Window Function Problems

---

### Session 12

**Video**

* 11:56:05 Window Value

### Learn

```sql
LAG()
LEAD()
FIRST_VALUE()
LAST_VALUE()
```

### Practice

Compare current sales with previous month.

---

# 📚 Phase 7: Advanced SQL (Week 5)

### Session 13

**Video**

* 12:40:34 Advanced SQL Techniques
* 12:58:04 Subqueries

### Practice

10 Subquery Problems

---

### Session 14

**Video**

* 14:18:08 CTE

### Learn

```sql
WITH sales_cte AS (...)
```

### Practice

Rewrite old queries using CTEs.

---

### Session 15

**Video**

* 15:35:02 Views
* 16:36:40 CTAS & Temp Tables

### Practice

Build temporary reporting tables.

---

# 📚 Phase 8: Database Development (Week 6)

### Session 16

**Video**

* 17:27:04 Stored Procedures
* 18:12:58 Triggers

### Practice

Create:

```sql
CREATE PROCEDURE
```

and

```sql
CREATE TRIGGER
```

examples.

---

### Session 17

**Video**

* 18:23:42 Indexes
* 20:20:31 Execution Plans
* 21:11:03 Partitions
* 21:43:39 Performance Tips

### Learn

Performance optimization.

Very important for Data Engineering interviews.

---

# 🚀 Projects (Weeks 7–8)

Do NOT skip.

### Project 1

* SQL Data Warehouse
* Bronze
* Silver
* Gold

### Project 2

* Exploratory Data Analysis

Create:

* Business Questions
* SQL Queries
* Insights

### Project 3

* Advanced Analytics

Portfolio-ready project.

Upload to GitHub.

---

# Best SQL Practice Websites (Recommended Order)

### 1. SQLBolt ⭐ (Best Beginner)

Difficulty: Easy

Great for learning syntax step by step.

[SQLBolt](https://sqlbolt.com?utm_source=chatgpt.com)

---

### 2. SQLZoo ⭐

Difficulty: Easy → Medium

Excellent JOIN practice.

[SQLZoo](https://sqlzoo.net?utm_source=chatgpt.com)

---

### 3. DataLemur ⭐⭐⭐

Difficulty: Medium

Very relevant for Data Analyst interviews.

[DataLemur](https://datalemur.com?utm_source=chatgpt.com)

---

### 4. LeetCode SQL ⭐⭐⭐

Difficulty: Medium → Hard

Most commonly asked interview SQL questions.

[LeetCode SQL Study Plan](https://leetcode.com/studyplan/top-sql-50/?utm_source=chatgpt.com)

---

### 5. HackerRank SQL ⭐⭐

Difficulty: Beginner → Intermediate

Good for timed practice.

[HackerRank SQL](https://www.hackerrank.com/domains/sql?utm_source=chatgpt.com)

---

# Suggested README Structure

```text
SQLMastery
│
├── Notes
│   ├── SQL Fundamentals
│   ├── Joins
│   ├── Functions
│   ├── Aggregation
│   ├── Window Functions
│   └── Advanced SQL
│
├── Practice
│   ├── SQLBolt
│   ├── SQLZoo
│   ├── LeetCode
│   └── DataLemur
│
├── Projects
│   ├── Data Warehouse
│   ├── EDA
│   └── Analytics
│
└── README.md
```

For your goal (entry-level Data Analyst/Data Scientist in Bangladesh), I would focus heavily on:

1. SELECT, WHERE, GROUP BY
2. JOINS
3. CASE WHEN
4. Window Functions
5. CTEs
6. EDA Project

Those six topics alone cover a large portion of SQL questions asked in analyst interviews.
