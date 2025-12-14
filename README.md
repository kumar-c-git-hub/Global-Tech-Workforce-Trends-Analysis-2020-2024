# 🌍 Global Tech Workforce Trends Analysis (2020–2024)

> **Tools:** Power BI | Excel | DAX | Power Query | Data Modeling
> **Domain:** Human Resources | Workforce Analytics

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![Excel](https://img.shields.io/badge/Tool-Excel-green)
![Domain-HR](https://img.shields.io/badge/Domain-HR-blue)
![Language-DAX](https://img.shields.io/badge/Language-DAX-orange)

---

## 🧩 Project Overview

This project analyzes **global technology-sector layoffs from 2020 to 2024**, focusing on workforce reductions, company size changes, funding impact, and geographic trends.
Using **Excel, Power Query, and Power BI**, raw layoff data was cleaned, transformed, and visualized to uncover meaningful insights into employment volatility and recovery patterns across the global tech ecosystem.

---

## 🎯 Project Objectives

### 1. Analyze Global Layoff Trends

Study worldwide tech layoff patterns (2020–2024), focusing on total employees laid off, companies affected, and year-wise layoff intensity.

### 2. Evaluate Workforce Impact

Assess changes in company headcount before and after layoffs using workforce size metrics and percentage reductions.

### 3. Understand Geographic Impact

Analyze layoffs across continents, countries, and regions to identify global hotspots and recovery trends.

### 4. Compare Industry & Company Performance

Compare layoffs across tech industries and company funding stages to highlight sector-specific vulnerabilities.

### 5. Interactive Data Exploration

Develop dynamic **Power BI dashboards** allowing users to filter insights by year, geography, industry, and company.

---

## 📂 Data Sources

**Source & Timeline:**

* 📊 *Worldwide Tech Employment Trends Dataset (2020–2024)*
* 🌐 *OpenDataBay*

**Domain:** Human Resources (HR)

---

## ❓ Problem Statement

* Analyze global technology layoffs to identify key workforce reduction trends.
* Evaluate layoffs across industries and funding stages to uncover risk-prone segments.
* Examine geographic distribution of layoffs and recovery patterns.
* Quantify workforce impact using pre- and post-layoff company sizes.
* Build an interactive dashboard to support strategic HR and business decisions.

---

## 🧾 Attribute Details

| **Attribute Name**         | **Data Type** | **Description**                         |
| -------------------------- | ------------- | --------------------------------------- |
| No.                        | Integer       | Unique identifier for each layoff event |
| Company                    | Categorical   | Name of the company                     |
| Location HQ                | Categorical   | Headquarters location                   |
| USState                    | Categorical   | U.S. state (if applicable)              |
| Country                    | Categorical   | Country of headquarters                 |
| Continent                  | Categorical   | Continent of headquarters               |
| LaidOff                    | Numeric       | Number of employees laid off            |
| Date Layoffs               | Date          | Layoff announcement date                |
| Percentage                 | Numeric       | Percentage of workforce laid off        |
| Company Size Before Layoff | Numeric       | Headcount before layoff                 |
| Company Size After Layoff  | Numeric       | Headcount after layoff                  |
| Industry                   | Categorical   | Tech industry segment                   |
| Stage                      | Categorical   | Company funding/lifecycle stage         |
| Money Raised (Millions)    | Numeric       | Total funding raised (USD)              |
| Year                       | Date          | Extracted year for trend analysis       |

---

## 🧹 Data Preprocessing Steps

1. **Data Collection:**
   Acquired global tech layoff data covering 2020–2024 from OpenDataBay.

2. **Data Cleaning (Excel & Power Query):**
   Removed duplicates, handled missing values, standardized date and numeric formats.

3. **Data Transformation:**
   Created calculated columns (Year), normalized Industry and Stage fields.

4. **Filtering & Sorting:**
   Filtered relevant tech layoffs and sorted records chronologically.

5. **Data Integration:**
   Consolidated all records into a single unified dataset for analysis.

6. **Data Modeling Preparation:**
   Conceptually structured data into fact (layoff events) and dimension tables (company, geography, industry, time).

---

## 🧮 Data Modeling & DAX (Power BI)

* **Model Design:**
  Implemented a **flat-table model** for simplicity and performance, supported by a dedicated **Measures Table** for centralized DAX calculations.

### 📐 Key DAX Measures

* **Total Laid Off** – Total employees laid off
* **Total Companies** – Distinct companies affected
* **Average Layoff %** – Mean layoff percentage
* **Total Size Before Layoff** – Workforce size before layoffs
* **Total Size After Layoff** – Workforce size after layoffs
* **Total Funding Raised** – Sum of funding (USD)
* **Recovery Rate %** – Post-layoff workforce ÷ Pre-layoff workforce

---

## 📊 Analysis & Visualizations

Created **interactive Power BI dashboards** using:

* Bar Charts
* Line Charts
* Pie & Donut Charts
* Tree Maps
* Maps
* KPI Cards
* Tables

### 🔍 Dashboard Highlights

* **Layoff Trends:** Year-wise layoffs and workforce recovery rates
* **Industry Impact:** Layoffs by industry and funding stage
* **Geographic Distribution:** Country & continent-level layoff intensity
* **Company Insights:** Top companies by layoffs and workforce reduction
* **Key Metrics:** KPIs summarizing total layoffs, companies affected, funding, and recovery

  <img width="978" height="549" alt="image" src="https://github.com/user-attachments/assets/ec5ec55a-2592-4e49-a87d-342df8742ff2" />


---

## 📈 Performance Insights

* 🌍 **North America** experienced the highest concentration of tech layoffs.
* 🏭 **Finance, Retail, and Healthcare tech** sectors were most impacted.
* 📉 Average layoff percentage hovered around **25%** across companies.
* 🏢 **Late-stage and Post-IPO firms** recorded significant workforce reductions.
* 💰 Funding availability showed a strong correlation with layoff severity.
* 📊 Recovery rates varied significantly by region, indicating uneven resilience.

---

## 🧠 Conclusion

The integration of **Excel and Power BI** enabled a comprehensive analysis of global technology sector layoffs (2020–2024).
Key takeaways include:

* Layoffs were heavily concentrated in specific industries and regions.
* Workforce recovery patterns differed widely across continents.
* Funding trends played a critical role in workforce decisions.

This project transformed complex employment data into **clear, actionable insights** for HR professionals, business leaders, and analysts to better understand workforce dynamics and plan strategically.

---

## 👩‍💻 Author

**KUMAR C**
*Data Analyst | Power BI Developer*

* 🌐 GitHub: [Kumar C](https://github.com/kumar-c-git-hub)
* 💼 LinkedIn: [kumar C](https://www.linkedin.com/in/kumar-c/)
* 📧 Email: [kumarak04122021@gmail.com](mailto:kumarak04122021@gmail.com)

---

## 📚 Tags

`#PowerBI` `#WorkforceAnalytics` `#HRAnalytics` `#LayoffsAnalysis`
`#DataVisualization` `#DAX` `#ExcelPowerQuery`


