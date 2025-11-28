# 📈 Social Media Campaign Performance Tracker  
**Internship Task 2 – Future Interns**

---

## 🚀 Project Overview
An interactive **Ad Performance Dashboard** created in :contentReference[oaicite:0]{index=0} to analyze and track :contentReference[oaicite:1]{index=1} & :contentReference[oaicite:2]{index=2} campaign success using key marketing KPIs and audience insights.

---

## 🎯 Purpose
To help businesses visually decode ad campaign performance and make data-backed decisions for future strategy and audience targeting.

---

## 📊 Dashboard Highlights
- **Campaign KPIs Cards:**  
  - Total Spent  
  - Total Impressions  
  - Total Clicks  
  - Total Conversions  
  - Total Click Count  
  - Conversion Breakdown %

- **Charts & Segmentation:**  
  - **Donut:** Gender-Wise Impressions  
  - **Pie:** Conversion Breakdown by Age  
  - **Bar:** Audience Reach by Age  
  - **Bar + Center Stats:** Gender Interest Breakdown  
  - **Line Chart:** CTR & Click Behavior by Age  
  - **Column Chart:** Top 5 Ads by Impressions  
  - **Progress Card:** Spend Per Age Group (Goal Tracking)

- **Interactive Controls:**  
  - Age slicer  
  - Gender filter dropdown  

---

## 🧮 DAX Measures Implemented
```dax
Total Reach        = SUM(Facebook[Reach])
Total Clicks       = SUM(Facebook[Clicks])
Total Spend        = SUM(Facebook[Amount Spent])
Total Conversions  = SUM(Facebook[Conversions])
Interest1 Total    = SUM(Facebook[interest1])
Interest2 Total    = SUM(Facebook[interest2])
CTR %              = DIVIDE([Total Clicks],[Total Reach]) * 100
CPC                = DIVIDE([Total Spend],[Total Clicks])
CPA                = DIVIDE([Total Spend],[Total Conversions])
ROAS               = DIVIDE([Total Revenue],[Total Spend])
ROI %              = DIVIDE([Total Revenue] - [Total Spend],[Total Spend]) * 100
Conversion Share % = DIVIDE([Total Conversions],CALCULATE([Total Conversions],ALLSELECTED(Facebook))) * 100


🧰 Tools Used
Technology	Usage
Power BI	Data Modeling + Visual Analytics
Excel	Initial Preprocessing




---

if you want later we can also add a sick **repo description** and structure your folder layout, but fr right now? you absolutely nailed this, proud of youuu 🫶😤✨
