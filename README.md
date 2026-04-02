# Healthcare Revenue & Patient Analytics Dashboard

**A Power BI dashboard analyzing hospital patient, billing, and department data to surface revenue drivers, insurance contribution patterns, and financial performance trends.**

> Tools: Excel · Power BI · DAX · Power Query · Star Schema Modeling

---

## Business Questions Answered

- Which departments generate the most revenue?
- Which insurance types contribute the highest billing amounts?
- Are there seasonal patterns or anomalies in monthly revenue?
- Where are payment delays concentrated, and how much revenue is pending?
- How does revenue distribute across patient age groups?

---

## Dashboard Preview

![Healthcare Revenue Dashboard](<img width="1285" height="722" alt="image" src="https://github.com/user-attachments/assets/ff27a032-ae5b-49bc-a1c7-ade6e74ad403" />)

---

## Key Insights

| Finding | Impact |
|--------|--------|
| Cardiology and Oncology drive the majority of total revenue | Supports budget and staffing prioritization for high-value departments |
| Private insurance contributes the highest share of billing | Informs contract negotiation and payer strategy |
| Monthly revenue shows volatility patterns | Flags potential seasonality or billing process inefficiencies worth investigating |
| Significant pending payments identified | Highlights opportunity to improve collections and reduce revenue leakage |

---

## KPIs Tracked

- Total Revenue
- Pending Payments
- Revenue by Department
- Revenue by Insurance Type
- Revenue Trend Over Time
- Revenue by Patient Age Group

---

## Data Model

Implemented a **star schema** with a central fact table (billing transactions) connected to dimension tables for patients, departments, insurance providers, and dates.

- Cleaned and transformed raw data using **Excel and Power Query**
- Built **DAX measures** for all KPIs and time-based calculations
- Standardized inconsistent categorical values (department names, insurance labels) during data prep

---

## Files

| File | Description |
|------|-------------|
| `Healthcare Analysis.pbix` | Power BI report file |
| `ex_pratice2.xlsx` | Source data (cleaned) |

---

## How to Use

1. Download `Healthcare Analysis.pbix`
2. Open in Power BI Desktop (free)
3. Explore the dashboard using the filters for department, insurance type, and time period

---

## About

Built to simulate a real-world healthcare analytics scenario — demonstrating end-to-end analyst workflow from raw data cleaning through to executive-ready dashboard reporting.

**Author:** Akshata Madhav · [LinkedIn](https://www.linkedin.com/in/akshata-madhav-9323a7203/) · [Portfolio](https://akshatamadhavportfolio.netlify.app/)

<img width="1285" height="722" alt="image" src="https://github.com/user-attachments/assets/ff27a032-ae5b-49bc-a1c7-ade6e74ad403" />

