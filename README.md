# 📊 Power BI Data Transformation & Analytics Project

> **“Shaping skills for scaling higher — Quality is our Motto.”**

This project demonstrates **end-to-end data extraction, transformation, modeling, and data quality analysis** using **Power BI (Power Query)**.  
It covers real-world data preparation techniques commonly used in **business intelligence, analytics, and reporting projects**.

---

## 🧩 Project Overview

The goal of this project is to:
- Extract data from multiple sources
- Clean and transform raw data
- Perform advanced Power Query operations
- Prepare analytics-ready datasets
- Ensure data quality and profiling

---

## 🛠 Tools & Technologies Used

- **Power BI Desktop**
- **Power Query (M Language)**
- **Excel (.xlsx)**
- **Web (HTML Tables)**
- **Folder-based data ingestion**

---

## 📂 Data Sources

1. **Web Source**
   - HTML table loaded from the web (e.g., Wikipedia GDP / COVID statistics)

2. **Sales Data (Folder Source)**
   - `Sales_Jan.xlsx`
   - `Sales_Feb.xlsx`
   - `Sales_Mar.xlsx`

3. **Employee Data**
   - Excel file containing:
     - EmployeeID
     - Name
     - Department
     - Region
     - Join Date

---

## 🔹 1. Data Extraction

- Loaded HTML tables directly from the web
- Loaded multiple Excel files using **Folder source**
- Combined monthly sales files using **Append Queries**
- Loaded employee dataset from a separate Excel file

---

## 🔹 2. Basic Transformations

- Removed blank rows and columns
- Promoted first row as headers
- Renamed columns to meaningful names
- Changed data types appropriately
- Used **Change Type with Locale** for:
  - Currency
  - Date columns
- Removed duplicates
- Filtered null values

---

## 🔹 3. Text Transformations

Applied text-cleaning techniques on customer names and address fields:
- `UPPER()`
- `LOWER()`
- `TRIM()`
- `CLEAN()`
- `REPLACE()`
- `SPLIT COLUMN BY DELIMITER`

Purpose:
- Standardize text
- Remove unwanted characters
- Improve data consistency

---

## 🔹 4. Numeric Transformations

- Rounded revenue columns to **2 decimal places**
- Created calculated column:
