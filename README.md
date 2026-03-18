#  Cancer Mortality & Patient Analysis Dashboard

## Overview
This dashboard explores cancer patient data, focusing on mortality rates, diagnosis groups, and survival outcomes. It visually presents insights on cancer vs. non-cancer deaths, patient counts, and mortality trends over time, while also highlighting patterns across gender, age, and health units.

---

##  Dashboard Pages

###  Home
- Navigation hub with buttons linking to each section of the report
- Project introduction and summary context

###  Insight
- KPI cards: Total Deaths, Cancer Deaths, Cancer Mortality Rate, Total Patients, Cancer Patients
- Bar chart showing cancer death count by primary diagnosis group
- Pie charts comparing cancer vs. non-cancer deaths and cancer share of total deaths
- Summary multi-row card for a quick snapshot of key figures
- Slicers: Health Unit, Gender, Age, Year, Diagnosis Group

###  Analysis
- Line chart tracking cancer deaths over time (by year)
- Donut chart comparing cancer survivors vs. total alive count
- Gauge visual displaying Cancer Mortality Rate
- KPI cards: Total Deaths, Cancer Deaths, Non-Cancer Deaths, Total Alive, Cancer Alive, Mortality Rate, Cancer Patients
- Slicers: Health Unit, Gender, Diagnosis Group, Age

###  Recommendation
- Data-driven insights and recommendations based on the analysis findings

---

##  Tools & Technologies
- **Power BI Desktop**
- **DAX** (Data Analysis Expressions)
- **Power Query** (data append/transformation via `Append1`)

---

##  Data Model

| Field | Description |
|---|---|
| `PrimDiagGroup` | Primary diagnosis/cancer type group |
| `cancer_death_count` | Number of deaths attributed to cancer |
| `noncancer_death_count` | Number of deaths not attributed to cancer |
| `total_death_count` | Total deaths across all causes |
| `Cancer_Mortality_Rate` | Rate of cancer deaths among patients |
| `total_patient` | Total number of patients |
| `Cancer_Patients` | Number of patients diagnosed with cancer |
| `Total_alive_count` | Total number of surviving patients |
| `cancer_Alive_count` | Number of cancer patients still alive |
| `Health Unit` | Health facility or unit |
| `Gender` | Patient gender |
| `Age` | Patient age |
| `RegDate` | Registration/diagnosis date |

---

##  Key Features
- Multi-page navigation with a dedicated Home page
- Dynamic slicers for Health Unit, Gender, Age, Year, and Diagnosis Group
- Cancer vs. non-cancer death comparison visuals
- Year-over-year cancer mortality trend analysis
- Survival outcome tracking (alive vs. deceased)
- Cancer Mortality Rate gauge for quick benchmarking

---

##  File
`Power_BI_Personal_Project.pbix`

---

##  How to Use
1. Download the `.pbix` file
2. Open with [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. Start on the **Home** page and use the navigation buttons to explore each section
4. Use the slicers to filter by health unit, gender, age group, year, or diagnosis type
