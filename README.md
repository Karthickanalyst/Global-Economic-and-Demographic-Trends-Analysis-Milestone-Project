🌍# Global-Economic-and-Demographic-Trends-Analysis-Milestone-Project

📌 Overview

This project explores global development patterns using economic, demographic, and social indicators. The analysis focuses on GDP, population trends, literacy, mortality, and migration from 1960 to 2016, using multiple datasets and interactive dashboards built in Power BI.

📁 Datasets Used

CountriesWorld Excel File – Combined indicators (GDP, literacy, phones, mortality, etc.)

GDP by Country (1960–2016) – Annual GDP per country

PopulationPerCountry – Annual population data

MetaData_Country – Country-region-income classifications

⚙️ Tools & Techniques

Power BI Desktop

Power Query for data transformation

DAX for calculated measures and KPIs

Data modeling (merging tables, relationships)

Statistical trend analysis (growth %, correlations)

📊 Dashboards Included

Global Economy – GDP growth, GDP per capita trends

Population Trends – Growth over time, top & bottom countries

Literacy & Technology – Literacy vs GDP, phones per 1,000

Regional Comparisons – Mortality, GDP, literacy by region

Country Profiles – Country-specific indicators

Migration & Demographics – Net migration, birth/death rates

🧠 Key Insights

High GDP countries show stronger literacy and digital access

Sub-Saharan Africa has the highest mortality and lowest literacy

Asia dominates population growth but with economic disparity

Net migration favors high-income nations

📈 Sample DAX Measures

Total GDP = SUM('GDP'[Value])
Avg Literacy = AVERAGE('CountriesWorld'[Literacy_Fixed])
Population Growth % =
    VAR First = CALCULATE(SUM('Population'[Value]), 'Population'[Year] = 1960)
    VAR Last = CALCULATE(SUM('Population'[Value]), 'Population'[Year] = 2016)
    RETURN DIVIDE((Last - First), First) * 100

✅ Recommendations

Prioritize education & health investments in low-literacy regions

Encourage tech access to boost digital literacy

Use GDP per capita alongside population trends for policy design

📂 Files in This Repo

GlobalInsights.pbix – Power BI report file

Data/ – Folder containing raw data sources (CSV, Excel)

README_GlobalInsights.md – This documentation

📧 Contact

Created by [Your Name][Your Email] | [GitHub URL] | [LinkedIn URL]

Note: This project is for academic and portfolio purposes only. Data sourced from public datasets.

