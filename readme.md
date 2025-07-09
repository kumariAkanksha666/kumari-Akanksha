# 🚕 Uber Supply-Demand Gap Analysis

This project analyzes Uber ride request data to identify supply-demand mismatches, peak request hours, and pickup point trends. The goal is to help Uber improve driver allocation during critical time periods.

---

## 📁 Project Files

| File Name                        | Description                                               |
|----------------------------------|-----------------------------------------------------------|
| Uber_Cleaned_Data.xlsx         | Cleaned dataset after removing duplicates and formatting timestamps |
| uber_queries.sql              | SQL file containing queries for demand/supply metrics     |
| Uber_EDA_Analysis.ipynb       | Python EDA notebook with visualizations using Pandas, Seaborn, Matplotlib |
| Uber_Insights_Report.pdf      | Final summary report with insights, charts, and business solutions |
| Uber_Project_Explanation.mp4  | 7–20 min recorded video explaining the project step-by-step |

---

## 📌 Problem Statement

Identify when and where Uber faces *supply shortages* (high cancellations / “No Cars Available”) by analyzing request timestamps, pickup points, and trip statuses.

---

## ✅ Project Steps

1. *Excel Data Cleaning*  
   - Fixed timestamp formatting using "Text to Columns"
   - Removed duplicate rows based on key columns
   - Added new columns: Request Hour and Request Date

2. *SQL Analysis*  
   - Total requests count  
   - Count of completed, cancelled, and unavailable trips  
   - Status breakdown by pickup point

3. *Python EDA (Google Colab)*  
   - Visualized request trends by hour and pickup location  
   - Analyzed cancellation/no-car patterns over time  
   - Created grouped bar charts and status distributions

4. *Insights Report (PDF)*  
   - Included charts, summary, and key recommendations

5. *Video Recording*  
   - Project explanation with voice and/or face  
   - Walkthrough of charts, code, and insights

---

## 📊 Key Charts

- Requests by Hour  
- Pickup Point Distribution  
- Trip Status Distribution  
- Cancelled/No Cars Over Time  
- Trip Status by Pickup Point (Grouped Bar Chart)

---

## 💡 Business Recommendations

- Increase driver availability during *peak hours*  
- Rebalance drivers dynamically between *City and Airport*  
- Improve *driver engagement* and *real-time assignment algorithms*

---

## 🔧 Tools Used

- *Excel (Microsoft 365)* – Data cleaning  
- *SQL (Notepad)* – Basic data analysis  
- *Python (Google Colab)* – Visual EDA using Pandas, Seaborn  
- *PowerPoint* – Final insights report  
- *Loom / OBS* – Video recording

- 📌 **[Click here to view the Google Colab Notebook](https://colab.research.google.com/drive/1Iqmey8hDbK4MCHsJ5F03ci0diy6V4wqo)**
