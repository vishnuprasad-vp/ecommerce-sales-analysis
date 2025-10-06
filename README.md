# 📊 E-Commerce Sales Analysis 
**From Data to Decisions: Trends, Profitability & Business Insights**

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)  
[![Pandas](https://img.shields.io/badge/Pandas-Data--Analysis-green)](https://pandas.pydata.org/)  
[![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-orange)](https://seaborn.pydata.org/)  
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Charts-yellow)](https://matplotlib.org/)  
[![GitHub](https://img.shields.io/badge/GitHub-Repo-black)](https://github.com/vishnuprasad-vp/ecommerce-sales-analysis.git)  

---

## 📌 Project Info  

**Author**: Vishnu Prasad V P  
**Course**: Data Analytics Final Project  
**Mentor**: Krishna Priya  
**Submission Date**: 13/09/2025  
**Repository**: [E-Commerce Sales Analysis](https://github.com/vishnuprasad-vp/ecommerce-sales-analysis.git)  

---

## 📖 Abstract  

This project analyzes **multi-source E-Commerce sales and operational datasets** (Amazon sales, International sales, Inventory, Pricing snapshots, Expenses, and Cloud Warehouse costs).  
The aim is to transform raw business data into **actionable insights** using **data preprocessing, exploratory data analysis (EDA), and visualizations**.  

🔑 **Key Findings:**  
- Amazon dominates revenue, but international markets are steadily growing.  
- A few **top categories and SKUs generate majority of sales**.  
- Order **cancellations significantly reduce profitability**.  
- **Logistics and warehousing are the largest expenses**.  
- Pricing strategies vary across marketplaces, impacting margins.  

---

## 📝 1. Introduction  

E-commerce generates vast amounts of sales, pricing, and expense data. Without analysis, this data cannot guide effective decision-making.  
This project demonstrates how to clean, process, and analyze such data to uncover **sales trends, anomalies, expense structures, and business opportunities**.  

### 🎯 Objectives  
- Clean and preprocess multi-source datasets.  
- Engineer useful business features (e.g., revenue by channel, shipped vs cancelled).  
- Perform EDA to reveal **sales, inventory, and expense patterns**.  
- Deliver actionable insights for business growth.  

---

## 📊 2. Data Description  

### 📂 Sources  
- Amazon Sales Report (domestic transactions)  
- International Sales Report (export transactions)  
- Sale Report (Inventory stock levels)  
- Pricing Files (May 2022 & March 2021 P&L snapshots)  
- Expense IIGF (operational expenses)  
- Cloud Warehouse Comparison Chart (logistics/warehousing costs)  

### 📏 Coverage & Granularity  
- Period: **2019–2024** (depending on file coverage)  
- Spatial: Domestic (Amazon) and International sales  
- Granularity: Transaction-level, product-level, and expense-level data  

---

## 🔧 3. Methodology  

### 🧹 Preprocessing  
- Removed redundant index columns and cleaned headers.  
- Converted **dates** to datetime and **amounts/quantities** to numeric.  
- Filtered cancelled/pending orders into a separate KPI dataset.  
- Derived new columns:  
  - Month, Year, Channel  
  - Flags (`is_shipped`, `is_cancelled`)  
  - Outlier detection (Amount IQR).  

### 📊 Exploratory Data Analysis  
- Monthly sales trends (Amazon vs International).  
- Category and SKU-level revenue analysis.  
- Order status distribution.  
- Expense and cost breakdown.  
- Pricing comparisons across platforms.  
- Inventory analysis and stock distribution.  
- Correlation matrix for business metrics.  

---

## 📈 4. Results & Key Insights  

- 📈 **Amazon is the leading revenue channel**, but exports show potential growth.  
- 🛒 **Top SKUs and categories dominate sales**, requiring targeted stock management.  
- 🚚 **Logistics and warehousing** form the bulk of expenses.  
- ❌ **Cancelled orders impact KPIs** and customer experience.  
- 💰 **Pricing varies across platforms**, suggesting optimization opportunities.  

---

## ⚠️ 5. Limitations  

- Limited timeframe for pricing & P&L files.  
- Manual standardization needed for inconsistent column names.  
- Expense data aggregated, lacking detailed categories.  

---

## 🌍 6. Societal & Business Implications  

### Societal Perspective  
- Efficient inventory reduces wastage.  
- Reliable delivery improves customer trust.  
- Optimized logistics reduces environmental impact.  

### Business Perspective  
- Enables KPI tracking (revenue, cancellations, margins).  
- Identifies high-performing SKUs for strategic investments.  
- Helps optimize pricing & discount strategies.  
- Supports warehouse/logistics cost negotiations.  

---

## ✅ 7. Conclusion  

This project demonstrates how **raw e-commerce datasets** can be processed, analyzed, and visualized to produce **business-ready insights**.  
The findings enable smarter decisions in **inventory planning, pricing, and expense management**.  

---

## 🚀 8. Future Work  

- Build **predictive sales models** (time-series forecasting).  
- Perform **region-level analysis** for micro-targeting.  
- Add **customer-level data** for loyalty and churn analysis.  
- Create automated **real-time dashboards**.  

---

## 📂 9. Repository Structure  

