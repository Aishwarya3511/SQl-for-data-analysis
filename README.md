# SQl-for-data-analysis
Use SQL queries to extract and analyze data from a database
# MySQL Project: Employee Data Analysis

This project contains SQL queries executed on the `parks_and_recreation` database using MySQL Workbench.

## 📂 Tables Used
- `employee_demographics`
- `employee_salary`

## 🔧 Tools
- MySQL Server 8.0
- MySQL Workbench

## ✅ Key Queries
- **SELECT with Expressions**
  ```sql
  SELECT first_name, age, (age + 10) * 2 FROM employee_demographics;
