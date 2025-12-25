# BigBasket Product Data – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on BigBasket product data to understand product distribution, pricing patterns, brand dominance, and discount behavior.  
The analysis focuses on **data cleaning, transformation, and insight generation** using **Power Query** and **Power BI**.

---

## 📂 Dataset
- ~27,000 product records
- Key attributes include:
  - Product name
  - Category & sub-category
  - Brand
  - Sale price & market price
  - Ratings
- Each row represents a **unique product listing**

---

## 🧹 Data Cleaning & Preparation (Power Query)
The following steps were performed in **Power Query**:

- Corrected data types for numeric and categorical columns
- Handled missing values:
  - Filled missing sale prices using market price (assumed no discount)
- Removed true duplicate records
- Standardized text fields (categories, brands)
- Created new features:
  - Discount amount
  - Discount percentage
  - Discount status (Discounted vs Not Discounted)
- Identified and reviewed pricing anomalies
- Created summary tables using Group By for category and brand analysis

---

## 📊 Exploratory Data Analysis
The EDA was structured across **two Power BI report pages**:

### Page 1 – Executive Overview
- Total products, brands, and categories
- Average selling price
- Top brands by product count
- Proportion of discounted vs non-discounted products

### Page 2 – Category & Discount Analysis
- Product count by category
- Average selling price by category
- Average discount by category
- Discount distribution for discounted products only

---

## 🔑 Key Insights
- **Beauty & Hygiene** dominates product listings, making it the most competitive category.
- **Baby Care** has the highest average selling prices, indicating a premium product segment.
- **Kitchen, Garden & Pets** receives the highest average discounts among categories.
- Most product discounts fall between **5%–25%**, while steep discounts above **50%** are rare.
- A small number of brands account for a large share of the product catalog.

---

## 🛠 Tools Used
- **Power Query** – Data cleaning, transformation, and feature engineering
- **Power BI** – Data visualization and dashboard creation
