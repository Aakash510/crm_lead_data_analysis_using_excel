# 📊 Real Estate CRM Lead Management & Analysis — 2024

> An MIS (Management Information Systems) assignment project analyzing 500 CRM leads for a real estate business. Covers end-to-end data cleaning, lead funnel tracking, agent performance evaluation, and an interactive Excel dashboard with pivot tables.

---

## 📁 Project Structure

```
crm-lead-analysis_using_excel/
│
├── MIS-crm-lead-analysis.xlsx       # Main Excel workbook (all sheets)
├── README.md                     # Project documentation
├── screenshots/                  # Dashboard & chart screenshots
│   ├── dashboard.png
│   ├── summary.png
│   └── pivot_table.png
└── report/                       # (Optional) Written report / PDF
    └── MIS_Analysis_Report.pdf
```

---

## 📌 Project Overview

This project simulates a real-world CRM (Customer Relationship Management) scenario for a real estate company. Raw lead data with inconsistencies was cleaned, analyzed, and visualized to derive business insights.

| Metric              | Value         |
|---------------------|---------------|
| Total Leads         | 500           |
| Converted Leads     | 184 (36.8%)   |
| Open / Callback     | 195           |
| Lost / Not Interested | 121         |
| Time Period         | Jan – Mar 2024 |

---

## 🗂️ Excel Workbook Sheets

### 1. `Raw CRM Dump`
Original messy data exported from a CRM system. Contains issues like:
- Inconsistent date formats (DD/MM/YYYY, YYYY-MM-DD, text dates)
- Inconsistent agent name spellings (R.Singh, Rohit S, rohit sharma)
- Mixed phone number formats (+91, 91, dashes, spaces)
- Inconsistent lead status values (converted, Converted, CONVERTED)
- Missing values in phone, email, city, and follow-up columns

### 2. `Cleaned Data`
Standardized version of the raw data after applying data cleaning rules:
- Uniform date format (DD-Mon-YYYY)
- Standardized agent names and lead statuses
- Normalized phone numbers
- Consistent Yes/No for Follow-up Done column

### 3. `Summary`
Aggregated metrics and KPIs:
- Lead status breakdown with share percentages
- Leads by source (Google Ads, Meta Ads, Referral, Walk-in, IVR, Organic)
- Agent-wise performance table with conversion rates and rankings

### 4. `Dashboard & Pivot Table`
Visual dashboard built with Excel pivot tables and charts:
- Conversion rate card
- Lead status distribution
- Source-wise lead count
- City-wise lead distribution
- Monthly trend (Jan–Mar 2024)
- Agent performance pivot

---

## 🔍 Key Insights

- **Top Converting Source**: Referral leads had the highest quality despite lower volume
- **Best Performing Agent**: Determined by conversion % (see Summary sheet)
- **Top Cities by Volume**: Delhi, Indore, Hyderabad, Pune, Bangalore
- **Monthly Trend**: Jan 2024 had the highest lead volume (168 leads)
- **Data Quality Issues Found**: ~20% of raw records had at least one formatting inconsistency

---

## 🛠️ Tools & Skills Used

- **Microsoft Excel** — Data cleaning, pivot tables, dashboard design
- **Excel Functions** — `IF`, `TRIM`, `PROPER`, `TEXT`, `COUNTIF`, `VLOOKUP`
- **Pivot Tables** — Multi-dimensional analysis by agent, source, status, city, month
- **Data Visualization** — Bar charts, donut charts, KPI cards in Excel
- **MIS Concepts** — CRM data management, lead funnel analysis, reporting

---

## 📚 Assignment Context

- **Subject**: Management Information Systems (MIS)
- **Assignment Type**: Data Analysis & Reporting
- **Domain**: Real Estate CRM
- **Dataset Size**: 500 leads across 10 columns

---

## 🚀 How to Use

1. Clone or download this repository
2. Open `MIS-crm-lead-analysis.xlsx` in Microsoft Excel (2016 or later recommended)
3. Start with the `Raw CRM Dump` sheet to see original data
4. Review `Cleaned Data` to understand transformations applied
5. Explore `Summary` for KPIs and metrics
6. View `Dashboard & Pivot Table` for visual insights

> ⚠️ Some Excel features (slicers, conditional formatting) may not render correctly in Google Sheets or LibreOffice.

---

## 👤 Author

**[Your Name]**
- 📧 aakashchourasiya81@gmail.com
- 🎓 SKGI, Indore
- 📅 Submitted: March 2026

---

## 📄 License

This project is submitted as part of an academic assignment. Not for commercial use.
