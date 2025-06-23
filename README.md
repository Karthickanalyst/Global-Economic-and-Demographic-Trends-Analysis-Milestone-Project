# 🌍 Global Insights: A Changing World

## 📌 Overview
This Power BI project analyzes global economic and demographic indicators from 1960 to 2016. It includes interactive dashboards on GDP, population, literacy, mortality, and migration — offering visual storytelling through data from over 100 countries.

## 📁 Datasets Used
- **CountriesWorld.xlsx** – Combined indicators (GDP per capita, literacy, phones, birth/death rates)
- **GDP_by_Country_1960_2016.xlsx** – Historical GDP data
- **PopulationPerCountry.csv** – Annual population by country
- **MetaData_Country.csv** – Region and income group classification

## ⚙️ Tools & Techniques
- **Power BI Desktop**
- Power Query (data cleaning & transformation)
- DAX measures (KPI calculations, growth %, YoY)
- Data modeling with multiple joins
- Statistical insights & pattern analysis

## 📊 Dashboards Included
1. **Global Economy** – Top GDP countries, growth trends
2. **Population Trends** – Population growth & density
3. **Literacy & Technology** – Literacy rate vs GDP, phones per 1000
4. **Regional Comparison** – Region-wise literacy, GDP, and mortality
5. **Country Profile Explorer** – KPI breakdown per country
6. **Migration & Demographics** – Net migration, birth/death rates

## 🧠 Key Insights
- High-income countries show higher literacy and digital access
- Sub-Saharan Africa faces high mortality and low literacy challenges
- Most global population growth is from lower-income countries
- Migration patterns reflect economic disparities

## 📈 Sample DAX Measures
```DAX
Total GDP = SUM('GDP'[Value])

Avg Literacy = AVERAGE('CountriesWorld'[Literacy_Fixed])

Population Growth % = 
VAR First = CALCULATE(SUM('Population'[Value]), 'Population'[Year] = 1960)
VAR Last = CALCULATE(SUM('Population'[Value]), 'Population'[Year] = 2016)
RETURN DIVIDE((Last - First), First) * 100
```
## Recommendations
- Strengthen education and healthcare in low-literacy regions
- Use GDP per capita + literacy as development indicators
- Encourage digital access for education
- Guide migration policies using data-backed population trends

📧 **Contact**
Created by Karthick.T
📧 karthickt646@gmail.com
🔗 https://github.com/Karthickanalyst
🔗 www.linkedin.com/in/karthickanalyst
