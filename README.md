# 🚖 Uber Fares Dataset Analysis – Power BI Project

**Course:** Introduction to Big Data Analytics (INSY 8413)  
**Instructor:** Eric Maniraguha  
**Student:** Shema Owen  
**Dataset Source:** [Kaggle – Uber Fares Dataset](https://www.kaggle.com/datasets/yasserh/uber-fares-dataset)  
**Date Submitted:** July 25, 2025

---

## 📌 Overview

This project analyzes the Uber Fares dataset to extract business insights using Python and Power BI. After cleaning and enriching the dataset, we built an interactive dashboard to visualize fare patterns, ride times, locations, and passenger behavior.

---

## ⚙️ Workflow Summary

### ✅ Python (Data Preprocessing)
- Removed nulls and rows with 0 values
- Feature engineering:
  - Hour, day, month, day_of_week, is_peak
  - Calculated trip distance using Haversine formula
- Exported final dataset: `uber_enhanced final one.csv`

### ✅ Power BI (Dashboard Creation)
- Imported cleaned CSV
- Visualized key patterns:
  - Fare distribution
  - Fare vs distance
  - Ride frequency by hour/day
  - Fare by passenger count
  - Pickup location map
- Used slicers to filter by day, month, passenger count, and peak hours

---

## 📊 Key Visuals

- **Histogram:** Fare amount distribution  
- **Line Chart:** Average fare by hour  
- **Scatter Plot:** Fare vs distance  
- **Box Plot:** Fare by day of week  
- **Map:** Pickup locations  
- **Bar Chart:** Rides per weekday  

---

## 🔍 Findings

- Most trips have 1–2 passengers and cost under $20  
- Fares peak during morning and evening commute hours  
- Fare and trip distance are strongly correlated  
- Weekends show slightly higher average fares  

---

## 💡 Recommendations

- Optimize pricing during weekend and evening peaks  
- Promote pooled/shared rides for short trips  
- Enhance driver coverage during early and late hours

---

## 📁 Files in Repository

# big-data-assignment-1
