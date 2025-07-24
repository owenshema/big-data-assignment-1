# Uber-Fares-Dataset-Analysis-using-Power-BI


# 📊 Uber Fares Dataset Analysis using Power BI

*Course:* Introduction to Big Data Analytics – INSY 8413  
*Instructor:* Eric Maniraguha (📧 [eric.maniraguha@auca.ac.rw](mailto:eric.maniraguha@auca.ac.rw)) 
*Group:* A 
*Tool:* Power BI Desktop  
*Dataset Source:* Uber Fares Dataset from Kaggle  
*Student Name:*SHEMA Owen 
*Student ID:* 26253
---

## 🚀 Project Objectives

The primary goal of this project is to analyze the Uber Fares dataset to uncover key insights about fare patterns, ride times, and operational metrics. Specific objectives include:

- Understanding the dataset through Exploratory Data Analysis (EDA)
- Cleaning and transforming the dataset using Python (Pandas)
- Enhancing the data with new analytical features
- Importing the enhanced dataset into Power BI for visualization
- Designing an interactive dashboard that highlights fare behavior across time and geography
- Presenting actionable insights for stakeholders

---
## 🧪 Step-by-Step Implementation

### 1. 📥 Data Collection & Loading
- Downloaded Uber dataset from Kaggle.
- Loaded into Jupyter Notebook using Pandas.
- Explored the structure, data types, null values, and duplicate rows.

<img width="1039" height="470" alt="basic" src="https://github.com/user-attachments/assets/fcf9b973-a5d1-466f-9166-926c35dd98ed" />


---

### 2. 🧹 Data Cleaning
- Removed missing values and extreme outliers (fare, distance).
- Converted timestamps into proper datetime objects.


<img width="819" height="425" alt="Screenshot 2025-07-24 063227 - Copy - Copy" src="https://github.com/user-attachments/assets/b01cd3fb-17f8-48c8-b281-31880db02064" />

---


### 3. 🧠 Feature Engineering
- Extracted pickup_hour, pickup_day, pickup_month, pickup_dayofweek.
- Calculated trip_distance_km using haversine formula.
- Exported enhanced dataset (uber_enhanced.csv).


<img width="458" height="390" alt="Image" src="https://github.com/user-attachments/assets/82c4370d-fac7-46c7-adf6-78286f2669bf" />
---
<img width="691" height="612" alt="fare amount" src="https://github.com/user-attachments/assets/4550b766-873d-413a-b484-d98a5a181559" />
### 4. 📊 Power BI Analysis

#### Visual 1: Number of Rides by Hour of Day
- Chart Type: Clustered Column
- Axis: pickup_hour
- Values: Count of fare_amount


 


<img width="1253" height="534" alt="histogram days" src="https://github.com/user-attachments/assets/50e4972a-b546-42c7-80b5-bfb0dbdeae97" />





#### Visual 2: Average Fare by Hour
- Chart Type: Clustered Column
- Axis: pickup_hour
- Values: Average of fare_amount


<img width="891" height="603" alt="fare vs hourday" src="https://github.com/user-attachments/assets/20bdd986-d326-4c6c-a850-d01b3c312195" />






#### Visual 3: Fare Distribution by Day of Week
- Chart Type: Clustered Bar Chart (Box plot not available)
- Axis: pickup_dayofweek
- Values: fare_amount









#### Visual 4: Scatter Plot (Fare vs Trip Distance)
- Chart Type: Scatter Plot
- X-Axis: trip_distance_km
- Y-Axis: fare_amount
- Details: passenger_count (optional)






#### Visual 5: Pickup Locations Map (Alternative)
- Used: Line and Stacked Column Chart due to map unavailability




---

### 5. 📈 Dashboard Design
- Unified visuals into interactive layout.
- Added slicers for time filters (hour, day, month).
- Formatted chart titles, colors, and tooltips.

<img width="750" height="406" alt="dashboard power bi" src="https://github.com/user-attachments/assets/00602550-28a1-47bf-ac93-59755c7c4c87" />



---

## 📖 Final Report Sections

- *Introduction*: Overview of project purpose and dataset.
- *Methodology*: Python for data cleaning + Power BI for analysis.
- *Analysis*: Key findings from each visual.
- *Results*: Trends and patterns discovered.
- *Conclusion*: Summary of fare behavior.
- *Recommendations*: Suggestions for Uber – peak hour strategies, price adjustments, etc.

📄 See: Report.pdf or Report.pptx

---

## 📬 Submission Checklist

- [x] Power BI File (.pbix)
- [x] Cleaned & enhanced CSV files
- [x] Jupyter Notebook used for Python processing
- [x] All screenshots in visuals/ or screenshots/ folder
- [x] README.md file (this file)
- [x] Final Report (PDF or PowerPoint)
- [x] GitHub repo public & link emailed to instructor

---

## ✅ Academic Integrity

All work submitted in this project reflects original analysis and visual design based on the raw Kaggle dataset. Any insights are generated through unique exploration using Python and Power BI.
