# 🚌 NYC Bus Delay & Breakdown Analysis (Excel Project)

This project was conducted as part of an analysis initiative for the **New York Division of Transportation** to improve the efficiency and reliability of the city’s bus system. Using Excel, we explored trends in bus delays and breakdowns to identify key problem areas and propose data-driven insights.

---

## 📁 Project Summary

- **Client**: New York Division of Transportation  
- **Tools Used**: Microsoft Excel  
- **Goal**: Understand the main causes and patterns behind frequent bus delays and breakdowns in NYC  
- **Data Source**: NYC Department of Transportation - Bus Operations Dataset  

---

## ❓ Key Business Questions Answered

### 1. 🚧 What are the most common reasons for delays and breakdowns?

- Created pivot tables and bar charts to summarize and rank reasons by frequency.
- Used conditional formatting to highlight high-frequency causes.

✅ **Result**:  
- Top causes included: Mechanical Issues, Traffic Congestion, Weather Conditions, and Driver Availability.

---

### 2. 🏙️ How do delay times vary by bus company and borough?

- Grouped data by bus company and borough using pivot tables.
- Calculated average delay time per group and visualized with clustered column charts.

✅ **Result**:  
- Certain boroughs like Manhattan and Queens had consistently longer delays.
- Delay durations varied significantly between bus contractors.

---

### 3. 📅 Is there a correlation between specific days of the week and delays or breakdowns?

- Added weekday column with `TEXT(Date, "dddd")` formula.
- Aggregated incidents by day using pivot tables and bar charts.

✅ **Result**:  
- Delays and breakdowns peaked on **Mondays** and **Fridays**, indicating operational strain at the start and end of the workweek.

---

## 🛠️ Excel Features Used

| Feature | Purpose |
|--------|---------|
| **Pivot Tables** | Grouping by reason, company, borough, and weekday |
| **Formulas** | `AVERAGEIFS()`, `TEXT()`, `IF()`, `COUNTIF()` |
| **Conditional Formatting** | Highlighting high-frequency values |
| **Charts** | Bar charts, column charts for comparative visuals |
| **Data Cleaning** | Removed duplicates, handled missing values, standardized reasons |

---

## 📸 Visuals Included

- 📊 Breakdown Causes Frequency Chart  
- 🗺️ Borough-wise Delay Duration Comparison  
- 📅 Weekday Incident Trend Bar Chart

> All visuals are included in the `visuals/` folder.

---


## 💡 Key Insights

- Operational issues are not evenly distributed across boroughs or contractors.
- Delay patterns are consistent with traffic congestion cycles and maintenance challenges.
- Weekdays show clear peaks in disruptions, useful for scheduling improvements.

---

## 🧑‍💼 About Me

I'm Giray Şengönül, a data analyst with strong Excel and data visualization skills. This project reflects my ability to turn real-world operational data into meaningful insights that support better public service planning and performance.

---

