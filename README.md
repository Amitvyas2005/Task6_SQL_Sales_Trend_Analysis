# Task6_SQL-_Sales-_Trend-_Analysis

## 🎯 Objective
To analyze monthly sales performance and product trends using SQL. The dataset contains online order records with details like `order_date`, `product_id`, `quantity`, and `price`.

---

## 🛠 Tools Used
- MySQL
- file importing usesSQL Import Wizard


---

## 🧹 Data Cleaning
1. **Check for NULL values** in key columns (`order_date`, `product_id`, `quantity`, `price`)
2. **Check for duplicate rows** based on full row match
3. **Calculate `amount`** = `quantity * price`
4. **Extract `year` and `month`** from `order_date` using `STR_TO_DATE`

---

## 📊 SQL Analysis Queries Overview

| # | Query Description |
|---|-------------------|
| 1 | Create and use database `sales_trend_analysis` |
| 2 | Import data into table `orders` |
| 3 | Check if data is loaded successfully |
| 4 | Count of NULL values in dataset |
| 5 | Detect duplicate rows |
| 6 | Add computed column `amount` (revenue) |
| 7 | Extract Year and Month from `order_date` |
| 8 | Monthly Revenue & Order Volume |
| 9 | Overall Revenue |
|10 | Orders per Product |
|11 | Revenue per Product |
|12 | Top 3 Revenue Months |
|13 | Monthly Average Order Value (AOV) |
|14 | Monthly Quantity Sold |
|15 | Top Earning Product |

---

## 📈 Sample Insights
- 📅 **Top Revenue Month**: Identified via total monthly sales.
- 💰 **Top Product**: Based on highest revenue generated.
- 🔍 **Sales Trends**: Revealed seasonal and monthly order behavior.

---

## 🧾 Final Notes
- `STR_TO_DATE(order_date, '%m/%d/%Y')` was used to handle date formatting correctly.
- Aggregations like `SUM()`, `AVG()`, `COUNT(DISTINCT ...)`, `GROUP BY`, `ORDER BY`, and `LIMIT` were used.
## 🧾 Files 
original csv file name as :online_sales_order_data.csv
Sql query file name as:sales_trend_analysis.sql
All Results table in csv :(result_table1 to 7)
a screenshot output file name as:Output Screenshots.pdf

