# Bus Transportation Analysis Dashboard
An interactive Excel dashboard analyzing bus transportation trends, usage, and performance to support operational decision-making.  
Built using Excel with Power Query and PivotTables, this project transforms raw transportation data into actionable insights for better planning and resource allocation.

Excited to share my latest project: an **interactive Bus Transportation Analysis dashboard built in Excel!**  
This project aimed to extract **actionable insights** from transportation data, empowering decision-makers and optimizing operations.  
Excel is a powerful and versatile tool, capable of transforming raw data into **dynamic, decision-ready insights**.

![Transportation Dashboard](./Transportation%20Dashboard%20Screenshot%20.png)


## Key Questions Addressed:
1️⃣ **Bus Utilization:** Identifying the busiest and least busy routes  
2️⃣ **Peak and Off-Peak Hours:** Determining the most and least congested times of operation  
3️⃣ **Year-over-Year Changes:** Analyzing trends and identifying areas for improvement

## Insights Revealed:
✅ The most congested route is the **East-West Express**, while the least congested is the **South Line**  
✅ The **peak time** of operation is **8:57 PM**, while the **off-peak** is **7:50 PM**  
✅ **Bus Utilization:**
- 24% Over-utilized  
- 22% Under-utilized  
- 45% Moderately-utilized  
- 9% Well-utilized  
✅ **Year-over-year change** is **-83.50%**, highlighting the need for strategic action

## Why This Matters:
📈 **Route optimization** and **resource allocation**  
😊 Enhanced **service efficiency** and **customer satisfaction**  
💲 Opportunities for **cost reduction** and **revenue growth**

## Data Model
The dashboard is built on a structured star schema for efficient reporting and analysis in Excel Power Pivot.  

 **Schema Overview:**
- **Fact Table:** `Facttable_ridership` — Tracks each bus trip, rider, date, and utilization  
- **Dimensions:**  
  - `Dim_routes` — Route details  
  - `Dim_buses` — Bus capacity & route link  
  - `Dim_demographics` — Rider age, gender, occupation  
  - `Dim_DateTable` — Calendar metadata  
  - `Calculations` — DAX measures used in the dashboard

 **Relationship Diagram:** 

![Data Model - Relationship Screenshot](Relationship%20Screenshot%20.png)

## Tools Used:
- **Microsoft Excel**
- **Power Query**
- **Power Pivot**
- **DAX**
- **PivotTables**
- **Data Visualization & Dashboard Design**

## Files Included:
- [`Bus Transportation Dashboard.xlsx`](./Bus%20Transportation%20Dashboard.xlsx) — The interactive Excel dashboard  
- [`Transportation Dashboard Screenshot.png`](./Transportation%20Dashboard%20Screenshot%20.png) — Dashboard preview image  
- [`Dataset-Excel Transportation.zip`](./Dataset-Excel%20Transportation.zip) — Raw dataset used for analysis (zipped)


## Let's Connect!
If you found this project interesting or useful, feel free to ⭐ star the repo or [connect with me on LinkedIn](https://www.linkedin.com/in/winnie-madikizella-data/).


