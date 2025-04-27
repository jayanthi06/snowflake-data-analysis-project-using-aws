
# ❄️ Snowflake Data Engineering Project

This project demonstrates how to leverage Snowflake as a cloud data warehouse to perform ETL processes, run analytical queries, and visualize business insights.

---

## 📚 Project Overview

- Loaded datasets into Snowflake using SnowSQL and Python.
- Built staging and analytics schemas for structured data modeling.
- Performed business-focused analytical queries (revenue trends, customer segmentation).
- Prepared clean datasets for downstream dashboarding and reporting.

---

## 🛠️ Tools and Technologies Used

**Snowflake**, **SnowSQL CLI**, **SQL**, **Python (optional for automation)**, **AWS S3 (for data staging)**

---

Flow:
- 🚀 Data landed into S3
- ⬇️ Loaded into Snowflake Staging Tables
- 🔄 Transformed into Analytics Layer
- 📈 Queried for insights

---

## 🚀 How to Execute

1. Create Database and Warehouses (use `create_tables.sql` under `schema/`).
2. Load datasets into Snowflake (`load_data_to_snowflake.sql`).
3. Run transformations and analytical queries (`snowflake_queries/`).
4. Export results for visualization if needed.

---

## 🔍 Key Analytical Outcomes

- Identified top revenue-generating customer segments.
- Analyzed monthly revenue trends and growth patterns.
- Modeled lifetime value of customers based on transaction behavior.

---

## 📑 Notes

- Ensure correct Snowflake role permissions for loading and querying.
- Follow warehouse sizing best practices based on data size.
- Used standard SQL 2016 supported by Snowflake.

---
