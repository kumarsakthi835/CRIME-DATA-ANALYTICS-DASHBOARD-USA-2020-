# 🚔 Crime Analytics Dashboard (USA – 2020)

## 📌 Project Overview

The **Crime Analytics Dashboard** is an end-to-end Data Analytics project developed using **Microsoft Excel** and **Microsoft Power BI**. The project analyzes crime incidents reported across the USA during **2020**, transforming raw data into meaningful business insights through data preprocessing, data modeling, DAX calculations, and interactive visualizations.

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

### 📊 Overall Crime Statistics

- **500** crime incidents were analyzed from the 2020 dataset.
- **323 cases (64.60%)** remain under investigation.
- **177 cases (35.40%)** have been successfully closed.
- The **average victim age is 33.12 years**.
- The dataset contains **21 unique crime categories** across **21 reporting areas**.

---

### 📅 Monthly Crime Trends

- **August** recorded the highest number of reported crimes with **261 incidents**.
- **April** was the second-highest month with **230 incidents**.
- Crime occurrences fluctuate throughout the year, indicating seasonal variations.

---

### 🚔 Crime Category Analysis

| Crime Category | Incidents |
|----------------|----------:|
| Aggravated Assault | **208** |
| Robbery | **65** |
| Weapon Offense | **36** |
| Domestic Violence | **34** |

**Insights**
- Aggravated Assault accounts for approximately **42%** of all reported crimes.
- Robbery is the second most frequently reported crime category.
- Violent crimes make up a significant share of the dataset.

---

### 👤 Victim Demographics

#### Gender Distribution

| Gender | Percentage |
|--------|-----------:|
| Male | **28%** |
| Female | **24%** |
| Unknown | **12%** |

**Insights**
- Male victims represent the largest identified victim group.
- Female victims account for nearly one-quarter of all reported victims.
- Some records contain unknown gender values, indicating incomplete demographic information.

---

#### Victim Age Distribution

| Age Group | Percentage |
|-----------|-----------:|
| Adult | **29.27%** |
| Child | **21.95%** |
| Young Adult | **21.95%** |
| Teen | **13.41%** |
| Senior Citizen | **13.41%** |

**Insights**
- Adults represent the largest victim group.
- Children and Young Adults together account for **43.90%** of victims.
- Crime affects all age groups, emphasizing the need for targeted public safety measures.

---

### 🔫 Weapon Analysis

| Weapon Category | Incidents |
|----------------------------|----------:|
| Strong-arm Methods | **106** |
| Handgun | **74** |
| Unknown Weapon | **36** |
| Unknown Firearm | **35** |
| Knife (≤6 inches) | **25** |
| Semi-Automatic Pistol | **24** |

**Insights**
- Strong-arm methods were involved in over **100** reported crimes.
- Handguns are the second most commonly used weapon.
- Firearms and knives collectively contribute to a significant portion of violent crimes.

---

### 📂 Investigation Status

| Status | Count | Percentage |
|--------|------:|-----------:|
| Open Cases | **323** | **64.60%** |
| Closed Cases | **177** | **35.40%** |

**Insights**
- Nearly **2 out of every 3** reported crimes remain unresolved.
- The current case closure rate is **35.40%**, highlighting opportunities to improve investigation efficiency.

---

### 📌 Business Recommendations

- Increase police patrols during **August** and other high-crime periods.
- Prioritize reducing the **323 pending investigations**.
- Focus crime prevention initiatives on **Aggravated Assault** and **Robbery**.
- Strengthen weapon control strategies for **Strong-arm assaults** and **Firearm-related crimes**.
- Improve data quality by reducing records with unknown demographic information.
- Use geographic crime analysis to allocate law enforcement resources more effectively.

### Major Findings

- August recorded the highest number of crime incidents.
- Aggravated Assault is the most common crime category.
- Male victims represent the largest identified victim group.
- Strong-arm methods are the most frequently reported weapon category.
- Approximately **65%** of reported cases remain open.

---

## 📁 Project Structure

Crime-Data-Analytics/
│
├── Dataset/
│   ├── Crime Data 1.csv
│   └── Cleaned Data.xlsx
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
- DAX Calculations
- Dashboard Development
- Data Visualization
- Business Intelligence
- Analytical Thinking

---

## 👨‍💻 Author

**Kumar S**

**Senior MIS Executive | Data Analyst**

- Data Analytics
