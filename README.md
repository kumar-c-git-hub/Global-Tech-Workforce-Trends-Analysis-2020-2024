🌍 Global Tech Workforce Trends Analysis (2020–2024)
Tools: Power BI | Excel | DAX | Power Query | Data Modeling
Domain: HR Analytics | Workforce Trends

![Power BI](https://img.shields.io/badge/Tool-Power%20https://img.shields.io/badge/Tool-Excel-greenhttps://img.shields.io/badge/Domain-HR%20https://img.shields.io/badge/Language-DAX Project Overview

This project analyzes global technology-sector layoffs (2020–2024) using Excel and Power BI to uncover workforce reduction patterns and industry-level employment dynamics.
The dataset covers company layoffs worldwide, exploring their impact across industries, countries, and funding stages.

Using Power Query for transformation and Power BI for visualization, the study provides actionable insights into tech workforce trends and recovery patterns.

🎯 Project Objectives
1. Analyze Global Layoff Trends
Study worldwide tech layoff volumes, affected companies, and year-wise intensity from 2020–2024.

2. Evaluate Workforce Changes
Compare pre‑ and post‑layoff company sizes, measuring the impact and recovery rates across organizations.

3. Understand Geographic Impact
Examine layoffs across continents, countries, and regions to identify global hotspots and resilience zones.

4. Compare Industry & Company Performance
Assess layoffs by industry segments and company funding stage, identifying top contributors and industry patterns.

5. Visualize Insights via Power BI
Create interactive dashboards to filter by year, geography, industry, and company, revealing employment dynamics and trends at multiple levels.

📂 Data Sources
Source & Timeline:

Worldwide Tech Employment Trends Dataset — OpenDataBay (2020–2024)

Domain: HR & Workforce Analytics

❓ Problem Statement
Analyze global technology-sector layoffs from 2020 to 2024 to identify key workforce reduction trends.

Assess layoffs across industries and funding stages to uncover vulnerable sectors.

Study geographic patterns of layoffs and recovery across continents and countries.

Evaluate workforce changes before and after layoffs for impact quantification.

Develop an interactive Power BI dashboard to explore employment dynamics and support strategic HR and business decisions.

🧾 Attribute Details
Attribute Name	Data Type	Description
No.	Integer	Unique identifier for each layoff event
Company	Text	Tech company name reporting the layoffs
Location HQ	Category	City or region of company headquarters
US State	Category	State (for U.S.-based companies)
Country	Category	Country of company headquarters
Continent	Category	Corresponding continent
Laid Off	Number	Total employees laid off in each event
Date Layoffs	Date	Date when layoff occurred or was announced
Percentage	Number	Workforce reduction percentage
Company Size Before Layoff	Number	Total employees before layoff
Company Size After Layoff	Number	Total employees after layoff
Industry	Category	Tech segment (e.g., Retail, Consumer, Transport)
Stage	Category	Company funding stage (Seed to Post-IPO)
Money Raised (in millions)	Number	Total funding raised in millions of USD
Year	Date	Extracted year for trend analysis
🧹 Data Preprocessing Steps
Data Collection: Collected global layoff data from OpenDataBay covering 2020–2024.

Data Cleaning: Removed duplicates, handled missing values, standardized numeric/date formats, and unified column names.

Data Transformation: Added Year column, normalized Industry and Stage names for consistency.

Filtering & Sorting: Filtered data to retain relevant tech-sector layoffs and maintained chronological order.

Data Integration: Combined multiple datasets into a single master table for unified Power BI analysis.

Data Modeling: Organized data conceptually into fact (layoff events) and dimension (company, geography, time) tables for reporting efficiency.

🧩 Data Modeling and DAX Implementation
Data Model Design:
Implemented a flat‑table model for simplicity, coupled with a measures table for DAX calculations.
This approach ensures efficient computation and structured management of KPIs across all visuals.

Key DAX Measures:

Total Laid Off: Sum of employees laid off.

Total Companies: Distinct count of affected companies.

Average Layoff %: Mean workforce reduction across companies.

Total Workforce (Before & After): Total employee counts to evaluate impact.

Total Funding Raised (₹M): Aggregate company funding in millions.

Recovery Rate %: Ratio of post‑layoff to pre‑layoff size, representing workforce resilience.

📊 Analysis & Visualizations
Dashboard Features:

Developed multiple interactive Power BI dashboards aligned with different analytical views.

Included filters, slicers, and bookmarks for flexible exploration by year, geography, and industry.

Designed pages for Overview, Trends & Funding, and Geographic & Company Insights.

Visual Types Used:

Bar & Line Charts → Layoff trends and recovery rates

Tree Maps → Industry & funding stage segmentation

Map Charts → Geographic distribution and impact intensity

Tables → Detailed company-level workforce statistics

KPI Cards → Key summary metrics (Layoffs, Companies, Avg % Reduction, Total Funding)

Highlights:

Visualized yearly global layoff volumes and recovery patterns.

Compared industry-level layoffs by size, funding stage, and geography.

Identified top 10 companies with highest layoffs by absolute and percentage impact.

Showcased funding trends relative to layoffs using dual-axis visuals.

<img width="978" height="549" alt="Overview" src="https://github.com/user-attachments/assets/0cdcfb66-3da4-47d0-a534-40d1c27ce399" />


📈 Performance Insights
🔹 Layoffs peaked during late 2022–2023, particularly in North America and Europe.

🧭 Finance, Retail, and Healthcare tech sectors experienced the largest workforce cuts.

💡 Post‑IPO and late‑stage companies were most affected — indicating market corrections.

🌍 Recovery rates varied geographically, with Asia showing quicker rebound trends.

📊 Funding trends correlated with layoff volumes, suggesting capital flow impact on workforce decisions.

🔁 Average global layoff percentage hovered at ~25%, with major firms like Amazon and Intel driving totals.

🧠 Conclusion
Through Excel preprocessing, Power Query transformation, and Power BI visualization, this project provides a 360° view of the Global Tech Workforce (2020–2024).
Key takeaways include:

High layoff concentration in Finance and Retail tech sectors.

Disproportionate impact on late‑stage firms and North American companies.

Uneven recovery across continents post‑2023.

The interactive Power BI dashboards empower HR leaders, investors, and policymakers to monitor workforce volatility and make insight-driven strategic decisions.

👩‍💻 Author
Kumar C
Data Analyst | Power BI Developer

🌐 GitHub: kumar-c-git-hub

💼 LinkedIn: kumar-c

📧 Email: kumarak04122021@gmail.com

If you found this project useful or would like to collaborate, feel free to connect!

📚 Tags
#PowerBI #DataAnalysis #TechLayoffs #WorkforceAnalytics
#DAX #DataVisualization #ExcelPowerQuery #HRAnalytics
