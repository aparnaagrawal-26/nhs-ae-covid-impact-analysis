# 🏥 A&E COVID-19 Impact Analysis (England)

**Project Type:** Data Analysis / Health Informatics  
**Tools Used:** Python, Jupyter Notebook, Pandas, Matplotlib, Seaborn  
**Data Sources:** NHS England, ONS COVID-19 Infection Survey  
**Time Range:** June 2015 – June 2023

---

## 🧩 Problem Statement

The COVID-19 pandemic significantly disrupted emergency healthcare systems across the UK.  
This project investigates how **Accident & Emergency (A&E)** attendances across NHS England evolved during and after the pandemic.

Key questions addressed:
- How did A&E attendances fluctuate in response to waves of COVID-19?
- Were there significant differences in attendance and delays across regions?
- How did standard-of-care metrics (e.g., wait time, admissions) change?
- What correlations exist between infection rates and A&E performance?

---

## 🔍 Project Objectives

- Conduct statistical and visual analysis of A&E attendance trends.
- Compare healthcare stress levels across North, Midlands, London, and South.
- Identify patterns in waiting times (e.g., >4h and >12h delays).
- Quantify the correlation between COVID positivity rates and emergency care outcomes.

---

## 🛠 Libraries and Tools Used

- [`pandas`](https://pandas.pydata.org/) – for data manipulation
- [`matplotlib`](https://matplotlib.org/) – for visualizations
- [`seaborn`](https://seaborn.pydata.org/) – for statistical plots
- [`openpyxl`](https://openpyxl.readthedocs.io/) – to read Excel `.xlsx` files
- Jupyter Notebook – for interactive analysis and documentation

---

## 📂 Excel File Used

- **Filename:** `Covid and A&E Attendance.xlsx`
- **Sheets:**
  - `England`: Aggregated national data for COVID and A&E trends
  - `Regions`: Disaggregated data by NHS England region

This file was the primary data source for all visualizations and statistical insights.

---

## 📊 Methods & Analysis

- **Boxplots** to show attendance variability across regions.
- **Time series plots** to highlight fluctuations in COVID cases vs A&E attendances.
- **Line charts** for delays, admission proportions, and system load.
- **Correlation heatmaps** to evaluate links between pandemic metrics and care quality.

---

## 🌍 Key Findings

- A&E attendances dropped sharply during the first COVID wave (Mar–May 2020).
- Despite high positivity rates in 2021–2022, attendances rebounded, reflecting adaptive capacity.
- London experienced the highest wait times post-COVID, likely due to higher density.
- Strong negative correlation between COVID case rates and percentage of patients seen within 4 hours.
- Wait times and care delays have increased post-2020, despite recovery in attendances.

---

## 🧠 Insights & Impact

- Data reveals how NHS England dynamically absorbed COVID shocks.
- Region-specific trends can guide **targeted surge capacity planning**.
- Highlights the importance of maintaining **urgent care throughput** during future health crises.

---

## 📁 Repository Contents

- `A&E_COVID_Impact_Analysis_England.ipynb`: Complete analysis with code, visuals, and markdown.
- `Covid and A&E Attendance.xlsx`: Raw data used in the study.
- Visual outputs for each major figure (Graphs 1.1 to 4.4).

---

## 📌 How to Run

1. Clone this repo or download the notebook.
2. Ensure you have Python 3.8+ and run:
   ```bash
   pip install pandas matplotlib seaborn openpyxl
