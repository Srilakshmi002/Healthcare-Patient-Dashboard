# Healthcare Patient Dashboard (Excel)

[![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Power Query](https://img.shields.io/badge/Power%20Query-0078D4?style=for-the-badge&logo=power-query&logoColor=white)](https://powerquery.microsoft.com/)

## Project Overview

This **interactive Excel dashboard** analyzes anonymized hospital data to uncover insights into:
- Patient demographics & condition prevalence
- Treatment patterns & physician performance
- Financial metrics (billing trends, revenue)
- Hospital operations (admissions, discharges, resource use)
- Patient flow & length of stay

Built for stakeholders to explore data dynamically with slicers, filters, KPIs, and conditional formatting. All visuals support drill-down and intuitive navigation.

**Dataset**: Kaggle Healthcare Dataset (~anonymized hospital records: patient info, diagnoses, treatments, billing).

## Workbook Structure

- **Home Page** — Welcome screen with hyperlinked navigation buttons
- **Objectives** — Project goals & key questions answered
- **Dashboard** — Main interactive view: charts, slicers, KPIs
- **Pivot Tables** — Backend dynamic tables for custom exploration

## Data Preparation

- **Source**: `healthcare_dataset.csv` (Kaggle)
- **Cleaning**: Power Query in Excel
  - Handled nulls/duplicates
  - Formatted dates, categories
  - Created calculated columns (e.g., length of stay, age groups)

## Key Features & Tools

- Interactive slicers & drop-down filters
- KPIs (e.g., total patients, avg length of stay, top conditions)
- Charts: bar, pie, line for trends
- Conditional formatting for quick insights
- Hyperlinked navigation for user-friendly experience

## Quick Start

1. Download or open `Healthcare-Patient-Dashboard .xlsx`
2. Enable macros/content if prompted (for hyperlinks/slicers)
3. Use slicers on Dashboard sheet to filter (e.g., by condition, age, billing amount)
4. Explore Pivot Tables sheet for ad-hoc analysis

## Screenshots

(Add these after uploading PNGs to repo)

![Dashboard Overview](dashboard_screenshot1.png)  
*Main dashboard with slicers and KPIs*

![Treatment Trends](treatment_trends.png)  
*Example: Top medical conditions & treatments*

## Future Work

- Migrate to Power BI or Tableau for advanced interactivity & sharing
- Add predictive elements (e.g., readmission risk via Excel ML or Python integration)
- Connect live to database (e.g., link to HealthConnect MySQL schema)
- Publish online version (e.g., via Excel Online or embed)
