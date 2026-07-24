# 🚔 Crime Data Analytics Dashboard (USA – 2020)

## 📌 Project Overview

The **Crime Data Analytics Dashboard** is an end-to-end Data Analytics project developed using **Microsoft Excel** and **Microsoft Power BI**. The project analyzes crime incidents reported across the USA during **2020**, transforming raw data into meaningful business insights through data preprocessing, data modeling, DAX calculations, and interactive visualizations.

The dataset was cleaned, transformed, and validated in Microsoft Excel before being imported into Power BI for dashboard development.

The dashboard enables users to identify crime trends, analyze victim demographics, monitor investigation status, evaluate weapon usage, and identify high-crime locations to support data-driven decision-making.

---

## 🎯 Project Objectives

- Analyze crime patterns across different reporting areas.
- Identify the most common crime categories.
- Analyze victim demographics by age and gender.
- Study monthly crime trends.
- Monitor investigation status (Open and Closed Cases).
- Analyze weapon usage patterns.
- Develop an interactive Power BI dashboard.
- Generate descriptive, diagnostic, predictive, and prescriptive insights.

---

## 📂 Dataset Information

| Item | Details |
|------|---------|
| **Dataset Name** | Crime Data |
| **Domain** | Crime Analytics / Public Safety |
| **Timeline** | 2020 |
| **File Format** | CSV |
| **Tools Used** | Microsoft Excel, Microsoft Power BI |

---

## 🛠 Tools & Technologies

### Microsoft Excel
Used for:
- Data Cleaning
- Data Transformation
- Data Validation
- Formatting
- Data Type Conversion
- Dataset Preparation

### Microsoft Power BI
Used for:
- Data Modeling
- Relationship Creation
- DAX Calculations
- KPI Development
- Interactive Dashboard Design
- Data Visualization
- Business Intelligence Reporting

---

## 🧹 Data Preprocessing

### Data Cleaning
- Renamed unclear column names.
- Converted date fields into Date format.
- Converted numeric time values into standard Time format.
- Assigned appropriate data types.
- Verified data consistency.
- Prepared the cleaned dataset for Power BI.

### Data Transformation
- Simplified lengthy crime descriptions.
- Categorized weapon descriptions into meaningful groups.
- Standardized victim gender values:
  - **M → Male**
  - **F → Female**
  - **Others → Unknown**
- Standardized time values for analysis.

### Data Quality Checks
- Verified date formats.
- Validated time conversion.
- Checked data consistency.
- Confirmed correct data types.
- Validated dataset readiness.

---

## 📊 Data Modeling

The project follows a **Star Schema** data model.

### Lookup Tables
- Crime Type Table
- Weapon Category Table

### Relationships
- Crime Data ↔ Crime Type Table
- Crime Data ↔ Weapon Category Table

**Relationship Type**
- One-to-Many
- Single Direction Filter

---

## 📈 DAX Calculations

### Calculated Columns
- Crime Month
- Crime Month Order
- Crime Month Year

### Measures
- Total Crimes
- Open Cases
- Closed Cases
- Average Victim Age
- Crime Types
- Total Areas

---

## 🎛 Dashboard Features

- Interactive KPI Cards
- Dynamic Slicers
- Cross Filtering
- Cross Highlighting
- Interactive Map
- Responsive Dashboard Layout
- Business-Oriented Reporting

---

## 🎚 Interactive Slicers

- Crime Month
- Area Name
- Victim Gender
- Crime Type
- Weapon Category

---

## 📌 Key Performance Indicators (KPIs)

- 🚔 Total Crimes
- 📂 Open Cases
- ✅ Closed Cases
- 👤 Average Victim Age
- 📑 Crime Types
- 📍 Total Reporting Areas

---

## 📊 Dashboard Visualizations

- 📈 Line Chart – Monthly Crime Trend
- 📊 Horizontal Bar Chart – Top Crime Categories
- 🍩 Donut Chart – Victim Gender Distribution
- 🍩 Donut Chart – Victim Age Distribution
- 🗺️ Map – Crime Area Distribution
- 📋 Table – Top Weapon Categories

---

## 📸 Dashboard Preview
<img width="581" height="327" alt="image" src="https://github.com/user-attachments/assets/3c954d9e-de01-4c1d-9e48-a3e9cd72bb7d" />

## 🔍 Key Insights

### Overall Statistics

| Metric | Value |
|--------|-------|
| Total Crime Records | 500 |
| Open Cases | 323 |
| Closed Cases | 177 |
| Average Victim Age | 33.12 Years |
| Crime Categories | 21 |
| Reporting Areas | 21 |

### Major Findings

- August recorded the highest number of crime incidents.
- Aggravated Assault is the most common crime category.
- Male victims represent the largest identified victim group.
- Strong-arm methods are the most frequently reported weapon category.
- Approximately **65%** of reported cases remain open.

---

## 💡 Business Recommendations

- Increase police patrols in high-crime areas.
- Prioritize long-pending investigations.
- Improve case closure rates.
- Strengthen crime prevention initiatives.
- Enhance public safety awareness programs.
- Use data-driven insights for effective resource allocation.

---

## 📁 Project Structure

```text
Crime-Data-Analytics/
│
├── Dataset/
│   └── Crime_Data.csv
│
├── Excel/
│   └── Data_Preprocessing.xlsx
│
├── PowerBI/
│   └── Crime_Analytics_Dashboard.pbix
│
├── Images/
│   └── Dashboard.png
│
├── Documentation/
│   └── Project_Documentation.pdf
│
└── README.md
```

## 🎓 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Validation
- Data Modeling
- Star Schema Design
- DAX Calculations
- Dashboard Development
- Data Visualization
- Business Intelligence
- Analytical Thinking

---

## 👨‍💻 Author

**Kumar S**

**Senior MIS Executive | Data Analyst**

### Tools & Skills
- Microsoft Excel
- Microsoft Power BI
- DAX
- Data Analytics
- Business Intelligence.
