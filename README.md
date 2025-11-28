# 📈 Social Media Campaign Performance Tracker

**Internship Task 2 – Future Interns**

---

## 🚀 Project Overview

An interactive **Ad Performance Dashboard** created in **Power BI** to analyze and track **Facebook** & **Instagram** campaign success using key marketing KPIs and audience insights.

---

## 🎯 Purpose

To help businesses visually decode ad campaign performance and make data-backed decisions for future strategy and audience targeting.

---

## 📊 Dashboard Highlights

### Campaign KPIs Cards:
- Total Spent
- Total Impressions
- Total Clicks
- Total Conversions
- Total Click Count
- Conversion Breakdown %

### Charts & Segmentation:
- **Donut Chart:** Gender-Wise Impressions
- **Pie Chart:** Conversion Breakdown by Age
- **Bar Chart:** Audience Reach by Age
- **Bar Chart + Center Stats:** Gender Interest Breakdown
- **Line Chart:** CTR & Click Behavior by Age
- **Column Chart:** Top 5 Ads by Impressions
- **Progress Card:** Spend Per Age Group (Goal Tracking)

### Interactive Controls:
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
```

---

## 🧰 Tools Used

| Technology | Usage |
|------------|-------|
| Power BI | Data Modeling + Visual Analytics |
| Excel | Initial Preprocessing |

---

## ✅ Skills Learned

- Marketing KPIs (Impressions, Reach, CTR, CPC, CPA, ROAS, ROI)
- Writing filter-aware DAX measures
- Audience segmentation
- Dark-theme BI dashboard design
- Interactive reporting

---

## 📁 Dataset

Campaign performance data imported in `CSV` format from Ads Manager (simulated/exported).

---

## 🤝 Credit

Task structure and learning guidance by **Future Interns** 💛

---

⭐ **Dashboard built for internship learning — feel free to reuse this README to document similar analytics builds!**
