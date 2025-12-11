
````markdown
# 📌 SQL Practice: ORDER BY Queries

This repository contains an SQL script that demonstrates how to use the **ORDER BY** clause in MySQL.  
It shows how to sort query results in ascending or descending order, and how to apply multi-column sorting.

---

## 📂 File Included

| File Name | Description |
|----------|-------------|
| **Q5_Order_BY.sql** | SQL script with examples of ascending, descending, and multi-column sorting |

---

## 📝 Overview

The script uses the `employees` database and performs various sorting operations on the `Employees` table.

### ✔️ Select All Records
```sql
USE employees;
SELECT * FROM Employees;
````

---

## 🚀 ORDER BY Usage Examples

### 🔹 Sort by Age (Default ASC)

```sql
SELECT * FROM Employees ORDER BY age;
```

### 🔹 Sort by Age (Explicit ASC)

```sql
SELECT * FROM Employees ORDER BY age ASC;
```

### 🔹 Sort by Age (DESC)

```sql
SELECT * FROM Employees ORDER BY age DESC;
```

### 🔹 Sort by Department Alphabetically

```sql
SELECT * FROM Employees ORDER BY department;
```

---

## 🎯 Multi-Column Sorting

These queries demonstrate sorting by multiple fields:

### 🔹 Sort by Age (DESC), then Name (ASC by default)

```sql
SELECT * FROM Employees 
ORDER BY age DESC, name;
```

### 🔹 Sort by Age (DESC), then Employee ID (ASC)

```sql
SELECT * FROM Employees 
ORDER BY age DESC, employee_id ASC;
```

This allows you to control sorting priority and create more structured query results.

---

## 📘 Purpose of This Script

This SQL file helps you understand:

* Sorting results using `ORDER BY`
* ASC vs DESC ordering
* How MySQL handles alphabetical sorting
* Multi-level sorting using multiple columns

It’s ideal for beginners practicing SQL data sorting and preparing for database-related interviews.

---

## 🤝 Contributing

You can extend this by adding:

* ORDER BY with LIMIT & OFFSET
* ORDER BY with WHERE clause
* ORDER BY with numeric + text fields combined

---

## 📄 License

This project is open-source and available for educational use.
