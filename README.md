# 🗄️ Customer Data Cleaning & Quality Analysis (T‑SQL)

## 📌 Overview
This project focuses on **data cleaning, standardization, and data quality analysis** using **T‑SQL**.  
The goal was to transform a raw customer dataset into a **clean, consistent, and analysis‑ready table**.

The dataset simulates common real‑world data issues such as missing values, inconsistent formats, duplicates, and invalid records.

---

## 📂 Data
- Raw customer dataset containing:
  - Personal details (name, email, phone, city)
  - Age and registration date
- Data includes inconsistent data types and invalid values

---

## 🎯 Objective
- Improve **data quality and consistency**
- Standardize formats and data types
- Identify and handle **invalid and duplicate records**
- Enrich data with calculated fields

---

## 🛠 Methodology
1. **Data type validation**
   - Standardized columns to appropriate types (VARCHAR, INT, DATE)
2. **Handling missing and invalid values**
   - Converted string‑based nulls (`'NULL'`, `'unknown'`) to proper NULL values
3. **Data standardization**
   - Normalized text formatting (names, cities, emails)
   - Cleaned and standardized phone numbers
4. **Date normalization**
   - Converted multiple date formats into a unified DATE format
5. **Data quality checks**
   - Identified invalid emails, unrealistic age values, and missing attributes
6. **Deduplication**
   - Detected duplicate records using window functions (`ROW_NUMBER`)
7. **Data enrichment**
   - Added calculated fields (e.g. full name, days since registration)
8. **Data quality flagging**
   - Classified records as complete or incomplete

---

## 🧰 Tools & Technologies
- T‑SQL
- Common Table Expressions (CTEs)
- Window functions
- Conditional logic (`CASE`)
- Data validation & cleansing techniques

---

## ✅ Outcome
A **cleaned, standardized, and enriched customer dataset** ready for further analysis, reporting, or BI integration.

---

## 💡 Key Skills Demonstrated
- Practical T‑SQL for analytics  
- Data cleaning & validation  
- Deduplication techniques  
- Data quality assessment  
- Analytical thinking  

---
