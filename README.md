# Nigeria_Education_Dashboard
A comprehensive Power BI analyses of Nigeria's education sector across 24 indicators from 1999 to 2023.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![World Bank](https://img.shields.io/badge/Data-World%20Bank-003087?style=for-the-badge)

---

## 📌 Project Overview

This project examines Nigeria's education performance across six thematic areas using publicly available World Bank Education Statistics data. The dashboard was built as part of a structured data analytics portfolio development initiative to demonstrate end-to-end analytical skills — from raw data sourcing to interactive dashboard delivery.

**Period Covered:** 1999 – 2023  
**Total Indicators Analysed:** 24  
**Dashboard Pages:** 6  
**Tools Used:** Microsoft Excel | Power BI Desktop  
**Data Source:** World Bank Education Statistics — Nigeria (NGA) via HDX  

---

## 📊 Dashboard Pages

| Page | Title | Description |
|------|-------|-------------|
| 1 | Enrolment Trends | School enrolment across pre-primary, primary, secondary & tertiary levels |
| 2 | Gender Gap Analysis | Male vs female enrolment share with parity benchmarking |
| 3 | Out of School & Completion | OOS children, gender exclusion rates, dropout analysis |
| 4 | Teacher Supply | Teaching workforce growth & gender representation |
| 5 | Funding & Literacy | Education spending vs GDP and adult literacy trends |
| 6 | Key Findings & Insights | Executive summary of all findings |

---

## 🔍 Key Findings

- 📈 **Primary enrolment grew 87%** — from 17.9M (1999) to 33.4M (2023)
- ♀️ **Gender parity never achieved** — female primary enrolment stands at 47.5%, below the 50% benchmark throughout the entire period
- 🚸 **9 million children** out of school in 2023 — girls face a 12 percentage point higher exclusion rate than boys
- 🎓 **Only 44%** of children complete lower secondary school — over half drop out before finishing junior secondary
- 👨‍🏫 **Teacher workforce grew** from under 200K to over 900K — female primary teachers now exceed parity at 55%
- 💰 **Nigeria spends just 0.32% of GDP** on education — far below UNESCO's recommended 4% minimum

---

## 🛠️ Skills Demonstrated

**Data Sourcing & Cleaning**
- Sourced open data from World Bank via Humanitarian Data Exchange (HDX)
- Filtered 449 indicators down to 24 relevant metrics
- Cleaned and transformed long-format data to wide format using Excel PivotTable
- Handled missing values, data gaps, and year range filtering

**Power BI Development**
- Built 6 interactive dashboard pages
- Created 14 DAX measures for accurate KPI card values
- Created calculated columns using IF/ISBLANK logic
- Applied dual Y-axis charts for multi-scale comparisons
- Configured cross-page Year Range Slicer using Sync Slicers
- Applied Analytics Pane reference lines (parity, UNESCO benchmark, full completion)

**Data Analysis & Storytelling**
- Identified gender equity trends across 24 years
- Benchmarked Nigeria's education spending against UNESCO standards
- Translated raw indicators into policy-relevant insights
- Documented findings in a full project report

---

## 📁 Repository Contents

```
nigeria-education-dashboard/
│
├── Nigeria_Education_Dashboard.pbix       # Power BI Dashboard file
├── Nigeria_Education_Dashboard.xlsx       # Cleaned dataset (Excel)
├── Nigeria_Education_Dashboard_Report.docx  # Full project report
├── screenshots/                           # Dashboard page screenshots
│   ├── page1_enrolment_trends.png
│   ├── page2_gender_gap.png
│   ├── page3_out_of_school.png
│   ├── page4_teacher_supply.png
│   ├── page5_funding_literacy.png
│   └── page6_key_findings.png
└── README.md
```

---

## 📸 Dashboard Preview

### Page 1 — Enrolment Trends
*![Page 1](https://github.com/Teabay7/Nigeria_Education_Dashboard/blob/main/Page_1.png)*

### Page 2 — Gender Gap Analysis
*![Page 2](https://github.com/Teabay7/Nigeria_Education_Dashboard/blob/main/Page_2.png)*

### Page 3 — Out of School & Completion
*![Page 3](https://github.com/Teabay7/Nigeria_Education_Dashboard/blob/main/Page_3.png)*

### Page 4 — Teacher Supply
*![Page 4](https://github.com/Teabay7/Nigeria_Education_Dashboard/blob/main/Page_4.png)*

### Page 5 — Funding & Literacy
*![Page 5](https://github.com/Teabay7/Nigeria_Education_Dashboard/blob/main/Page_5.png)*

### Page 6 — Key Findings & Insights
*![Page 6](https://github.com/Teabay7/Nigeria_Education_Dashboard/blob/main/Page_6.png)*

---

## 📂 Data Source

| Detail | Info |
|--------|------|
| Platform | Humanitarian Data Exchange (HDX) |
| Publisher | World Bank |
| Dataset | Nigeria Education Indicators |
| Format | CSV |
| Access | Free, no login required |
| URL | https://data.humdata.org |

---

## ⚙️ How to Open the Dashboard

1. Download and install **Power BI Desktop** (free) from: https://powerbi.microsoft.com/desktop
2. Clone or download this repository
3. Open `Nigeria_Education_Dashboard.pbix` in Power BI Desktop
4. The dataset is embedded — no additional setup required
5. Use the **Year Range Slicer** on any page to filter all pages interactively

---

## 📄 Project Report

A full written report documenting the entire project lifecycle — from data sourcing to key findings — is available in `Nigeria_Education_Dashboard_Report.docx`. The report covers:

- Project objectives
- Data sourcing methodology
- Data cleaning steps
- Indicator selection justification
- Dashboard design decisions
- All DAX measures used
- Key findings and insights
- Limitations and recommendations

---

## 👤 About the Analyst

**Uthman Toyyib Oluwadamilare**  
Data Analyst | Researcher | Educator  
- 🛠️ Skills: Excel | Power BI | SPSS | SQL | Python

📧 uthmantoyyib4@gmail.com  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/toyyibuthman) 

---

## 📜 License

This project is open for viewing and educational reference. Please credit the analyst if you reference or build upon this work.

---

*⭐ If you found this project useful or insightful, please consider giving it a star!*
