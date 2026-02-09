# SLA Compliance & On-Time Performance Dashboard (Excel)

## Project summary
This project is an Excel dashboard built to review last-mile delivery performance. It focuses on **SLA compliance** and **on-time delivery rate**, with performance segmented by **traffic condition** and **service area**. The workbook is organized like a simple business report: KPI strip at the top, charts for analysis, and an **Insights & Actions** section for quick takeaways.

## What’s included
### Dashboard highlights (Sheet: `05_Dashboard`)
**KPI strip**
- Total Deliveries  
- On-Time %  
- Avg Delivery Time (min)  
- Avg SLA Target (min)

**Charts**
- On-Time % by Traffic  
- On-Time % by Area  
- Late Delivery Severity (0–15, 15–30, 30–60, 60+ mins, On time/early)

**Insights & Actions**
A short summary box that explains the main observations from the visuals and suggests practical next steps.

## Tools / skills used
- Microsoft Excel  
  - PivotTables and PivotCharts  
  - Data cleaning and formatting  
  - Simple helper columns / categorization (e.g., SLA status, delay buckets)  
  - Dashboard layout and KPI reporting  

## Workbook structure (sheet tabs)
- `README_First` – overview + how to use  
- `00_Amazon_Delivery_Dataset` – raw dataset  
- `01_Clean_Dataset` – cleaned dataset used for analysis  
- `02_Data_Dictionary_Sheets` – column definitions and KPI notes  
- `03_SLA` – SLA mapping table (Area × Traffic → SLA_Minute)  
- `04_Pivot` – PivotTables powering the charts/KPIs  
- `05_Dashboard` – final dashboard  

## How to view
1. Download `SLA_Compliance_OnTime_Performance_Excel_Dashboard.xlsx` from this repo.
2. Open in Excel and go to the `05_Dashboard` sheet.

## Screenshots
![Screenshot 1](./Screenshots/Screenshot%20(1).png)
![Screenshot 2](./Screenshots/Screenshot%20(2).png)
