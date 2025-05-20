# Data Cleaning with SQL (SQLite)

**Tools Used:** SQLite, DB Browser for SQLite  
**Dataset:** 125+ synthetic customer records

## 📌 Objective

Clean a raw dataset by removing duplicate rows, handling missing values, and preparing it for analysis using SQL in a local SQLite environment.

---

## 🧼 Cleaning Steps

- ✅ Removed duplicate rows using `SELECT DISTINCT`
- ✅ Replaced missing `Subscription` values with `'Basic'`
- ✅ Replaced missing `AmountPaid` with `0.00`
- ✅ Deleted records missing `Name` or `Email`
- ✅ Verified nulls were removed and exported clean data

---

## 🔄 Process Summary

1. Imported raw CSV file into SQLite using DB Browser
2. Ran SQL queries to clean and transform data
3. Exported final results to `Data_Cleaning_SQL_Cleaned.csv`

---

## 📂 Files

| File                             | Description                      |
|----------------------------------|----------------------------------|
| Data_Cleaning_SQL_Project_Raw.csv     | Original imported dataset        |
| Data_Cleaning_SQL_Cleaned.csv         | Final cleaned dataset            |
| README.md                        | Project overview and explanation |

---

## 💡 Outcome

A fully cleaned, analysis-ready dataset created entirely with SQL.  
This project showcases SQL fundamentals in a local database environment and is part of my data analytics portfolio.

---

*Project by qumonie *  
