# 🐘 PostgreSQL Preparation Challenge (10 Days)

A structured 10-day learning journey focused on mastering PostgreSQL fundamentals, SQL querying, database design, performance optimization, and interview-ready explanations.

This repository contains daily notes, practical examples, hands-on exercises, real-world scenarios, and official PostgreSQL resources.

🎯 **Goal:** Build a strong understanding of PostgreSQL and develop the ability to explain database concepts clearly in technical interviews.

---

# 📅 Progress Tracker

* [ ] Day 1 – PostgreSQL Fundamentals
* [ ] Day 2 – SQL Querying Essentials
* [ ] Day 3 – Joins Deep Dive
* [ ] Day 4 – Aggregations & Grouping
* [ ] Day 5 – Subqueries & CTEs
* [ ] Day 6 – Window Functions
* [ ] Day 7 – Indexing & Query Optimization
* [ ] Day 8 – Transactions & Concurrency
* [ ] Day 9 – Database Design & Normalization
* [ ] Day 10 – Advanced PostgreSQL

---

# 📚 Official Learning Resources

## PostgreSQL Documentation

The best PostgreSQL resource available.

* https://www.postgresql.org/docs/

## PostgreSQL Tutorial

* https://www.postgresql.org/docs/current/tutorial.html

## SQL Language Reference

* https://www.postgresql.org/docs/current/sql.html

---

# 🧩 Practice Resources

## PostgreSQL Tutorial

https://www.postgresqltutorial.com/

---

# 📂 Repository Structure

```
postgresql-interview-prep/
│
├── Day-01-Fundamentals/
├── Day-02-SQL-Basics/
├── Day-03-Joins/
├── Day-04-Aggregations/
├── Day-05-CTEs/
├── Day-06-Window-Functions/
├── Day-07-Indexing/
├── Day-08-Transactions/
├── Day-09-Normalization/
├── Day-10-Advanced-PostgreSQL/
│
└── README.md
```

---

# Day 1: PostgreSQL Fundamentals

## Topics

* Database vs Schema
* Tables, Rows, Columns
* Data Types
* Primary Keys
* Constraints
* Foreign Keys

## Official Resources

* [PostgreSQL Tutorial](https://neon.com/postgresql/tutorial)
* SQL Language Basics

## Tasks

* [x] ~~Create a Student table~~~~
* [x] ~~Create a Product table~~
* [x] ~~Add Primary Keys~~
* [x] ~~Add Constraints~~
* [x] ~~Design a simple E-Commerce schema~~

## Interview Focus

### What is a Primary Key?

A Primary Key uniquely identifies each row in a table and prevents duplicate records.

### CHAR vs VARCHAR vs TEXT

| Type    | Description             |
| ------- | ----------------------- |
| CHAR    | Fixed-length string     |
| VARCHAR | Variable-length string  |
| TEXT    | Unlimited-length string |

---

# Day 2: SQL Querying Essentials

## Topics

* SELECT
* WHERE
* ORDER BY
* LIMIT
* DISTINCT
* Aliases

## Official Resources

* Querying a Table
* SELECT Documentation

## Tasks

* [x] ~~Solve 20 SQL problems~~
* [x] ~~Filter records~~
* [x] ~~Sort records~~
* [x] ~~Use aliases~~

## Interview Focus

### SQL Execution Order

1. FROM
2. WHERE
3. GROUP BY
4. HAVING
5. SELECT
6. ORDER BY
7. LIMIT

### WHERE vs HAVING

WHERE filters rows before grouping.

HAVING filters groups after aggregation.

---

# Day 3: Joins Deep Dive

## Topics

* INNER JOIN
* LEFT JOIN
* RIGHT JOIN
* FULL JOIN
* SELF JOIN

## Official Resources

* Joins Between Tables

## Tasks

* [ ] Employee-Manager relationship
* [ ] Customer Orders Query
* [ ] Join 3+ tables

## Interview Focus

### INNER JOIN vs LEFT JOIN

INNER JOIN returns matching records only.

LEFT JOIN returns all records from the left table plus matching rows.

---

# Day 4: Aggregations & Grouping

## Topics

* COUNT()
* SUM()
* AVG()
* MIN()
* MAX()
* GROUP BY
* HAVING

## Official Resources

* Aggregate Functions

## Tasks

* [ ] Sales Dashboard Queries
* [ ] Revenue Reports
* [ ] Department Statistics

## Interview Focus

### GROUP BY vs DISTINCT

DISTINCT removes duplicates.

GROUP BY groups records for aggregation.

---

# Day 5: Subqueries & CTEs

## Topics

* Scalar Subqueries
* Correlated Subqueries
* CTEs
* Recursive CTEs

## Official Resources

* WITH Queries (CTEs)

## Tasks

* [ ] Rewrite Subqueries as CTEs
* [ ] Recursive Employee Hierarchy
* [ ] Sales Ranking Query

## Interview Focus

### CTE vs Subquery

CTEs improve readability and maintainability.

---

# Day 6: Window Functions

## Topics

* ROW_NUMBER()
* RANK()
* DENSE_RANK()
* LEAD()
* LAG()
* PARTITION BY

## Official Resources

* Window Functions Documentation

## Tasks

* [ ] Top 3 Employees per Department
* [ ] Running Totals
* [ ] Month-over-Month Comparison

## Interview Focus

### GROUP BY vs Window Functions

GROUP BY collapses rows.

Window Functions retain row-level details.

---

# Day 7: Indexing & Query Optimization

## Topics

* B-Tree Index
* Composite Index
* Partial Index
* Query Plans
* EXPLAIN ANALYZE

## Official Resources

* Indexes
* Performance Tips

## Tasks

* [ ] Create Indexes
* [ ] Compare Query Speed
* [ ] Analyze Execution Plans

## Interview Focus

### Why Use Indexes?

Indexes reduce disk scans and improve query performance.

### Why Too Many Indexes Hurt?

They increase storage and slow INSERT, UPDATE, DELETE operations.

---

# Day 8: Transactions & Concurrency

## Topics

* ACID Properties
* Transactions
* COMMIT
* ROLLBACK
* Isolation Levels
* Locks

## Official Resources

* Concurrency Control
* Transaction Isolation

## Tasks

* [ ] Banking Transaction Example
* [ ] Rollback Scenario
* [ ] Isolation Level Testing

## Interview Focus

### ACID

* Atomicity
* Consistency
* Isolation
* Durability

### Common Problems

* Dirty Reads
* Non-repeatable Reads
* Phantom Reads

---

# Day 9: Database Design & Normalization

## Topics

* 1NF
* 2NF
* 3NF
* BCNF
* Denormalization

## Official Resources

* Constraints
* Foreign Keys

## Tasks

* [ ] Normalize E-Commerce Schema
* [ ] Design Inventory Database
* [ ] Create ER Diagram

## Interview Focus

### Why Normalize?

To reduce redundancy and improve data integrity.

### When Denormalize?

For reporting and performance optimization.

---

# Day 10: Advanced PostgreSQL

## Topics

* Views
* Materialized Views
* Partitioning
* JSONB
* Triggers
* Stored Procedures

## Official Resources

* JSON Types
* Partitioning
* Views

## Tasks

* [ ] Create Materialized View
* [ ] Store JSON Data
* [ ] Implement Table Partitioning
* [ ] Build Trigger Example

## Interview Focus

### JSON vs JSONB

JSONB stores data in binary format and supports indexing.

### View vs Materialized View

View executes query every time.

Materialized View stores query results physically.

### Partitioning vs Sharding

Partitioning splits tables inside one database.

Sharding distributes data across multiple databases.

---

# 🎯 End-of-Challenge Deliverables

* [ ] PostgreSQL Notes
* [ ] SQL Practice Collection
* [ ] Join Examples
* [ ] Window Function Examples
* [ ] Query Optimization Examples
* [ ] Transaction Scenarios
* [ ] Normalization Case Studies
* [ ] Performance Tuning Notes
* [ ] Advanced PostgreSQL Notes

---

# 📊 Skills Covered

✅ PostgreSQL Fundamentals

✅ SQL Queries

✅ Joins

✅ Aggregations

✅ CTEs

✅ Recursive Queries

✅ Window Functions

✅ Indexing

✅ Query Optimization

✅ Transactions

✅ Concurrency Control

✅ Normalization

✅ Database Design

✅ JSONB

✅ Views

✅ Materialized Views

✅ Partitioning

✅ PostgreSQL Performance Tuning

---

# 🏆 End Goal

By the end of this challenge, you should be able to confidently explain:

* Joins
* Window Functions
* CTEs
* Indexing
* Query Optimization
* ACID Properties
* Isolation Levels
* Database Normalization
* JSONB
* Partitioning
* PostgreSQL Performance Tuning

with real-world examples instead of memorized definitions.
