# Employees SQL — Aggregates & NULL Handling

This repo contains a single MySQL practice script that runs common analytical queries against the classic **`employees`** sample database.  
You’ll practice:

- Counting distinct values
- Summing and averaging with date filters
- Finding minimum and maximum keys
- Rounding averages
- Handling missing data with `COALESCE` and `IFNULL`
- Producing clean, ordered result sets

> **Script:** `Aggregate Functions.sql`

---

## 1) Prerequisites

- MySQL 8.x (or 5.7+)
- The **`employees`** sample database installed and loaded
  - Verify with: `SHOW DATABASES;` then `USE employees;`
- A MySQL client (CLI, Workbench, or any GUI)

---

## 2) How to Run

From CLI:
```sql
SOURCE Aggregate Functions.sql;
