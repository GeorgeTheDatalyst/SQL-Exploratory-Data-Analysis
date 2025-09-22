# 📊 SQL Data Exploration & Analysis Toolkit

This repository contains a comprehensive SQL script designed to explore and analyze a dimensional data warehouse. It covers metadata inspection, dimension profiling, date analysis, business metrics, magnitude comparisons, and ranking insights using SQL Server syntax.

---

## 🧠 Purpose

This toolkit is ideal for:
- Understanding the structure and content of a database
- Profiling dimensions and measures
- Generating summary reports
- Performing ranking and performance analysis
- Supporting dashboard design and business intelligence workflows

---

## 📁 Contents

The SQL script is organized into the following sections:

---

### 1. 🗂️ Database Exploration

Explore metadata to understand the structure of the database.

```sql
-- Explore all tables
SELECT * FROM INFORMATION_SCHEMA.TABLES;

-- Explore all columns
SELECT * FROM INFORMATION_SCHEMA.COLUMNS;
# SQL-Exploratory-Data-Analysis
