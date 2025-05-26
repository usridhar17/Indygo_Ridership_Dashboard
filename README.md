# IndyGo Ridership Power BI Dashboard

This project was developed as part of the Information Visualization course at Indiana University in collaboration with **IndyGo**, the public transportation agency serving Indianapolis.

🔗 **[View the Dashboard](https://indiana-my.sharepoint.com/:u:/r/personal/usridhar_iu_edu/Documents/IndyGo_Ridership_Dashboard_Elite_Analysts.pbix?csf=1&web=1&e=JchdPV)**  

![image](https://github.com/user-attachments/assets/4e1f65b0-359e-4aba-aefc-c084ad3534a8)

![image](https://github.com/user-attachments/assets/08211c3a-4e59-4193-b3b3-b231e206bf1d)

![image](https://github.com/user-attachments/assets/e10bc2b5-8e37-4abd-a7eb-8ffb4afe165c)

![image](https://github.com/user-attachments/assets/5c7026a5-0fa3-42b3-8535-9c73d52f7278)

---

##  Project Objective

The goal of this project is to design and deploy a comprehensive **Ridership Dashboard** for IndyGo as a foundational component of a broader open data platform initiative.

Public transit agencies like IndyGo are under increasing pressure to operate transparently, make data-informed decisions, and respond to community needs. Although operational data is collected, it is often underutilized or inaccessible.

This dashboard aims to:

- Centralize and visualize **stop-level ridership data** across key dimensions: time, route, geography, and service type.
- Provide **IndyGo planners, analysts, and city officials** with actionable insights to improve route planning, service frequency, and resource allocation.
- **Engage the public** and increase transparency by making data trends accessible and easy to interpret.

---

##  Dashboard Highlights

- **Total Ridership** by workday type, year, month, and route
- **Stop-wise and Route-wise comparisons**
- **Time-based trends** (week number, day of week, monthly patterns)
- **Interactive map visualizations** with drill-down filtering

---

##  Dataset Overview

- **Source**: GPS & Automatic Passenger Counters (APCs)
- **Tables Used**:
  - `FactSegmentAdherence`
  - `DimStop`
  - `DimRoute`
  - `DimDate`
  - `DimTrip`
  - `DimVehicle`
  - `DimBlock`
- **Timeframe**: 2023–2024
- **Format**: CSV files with an accompanying data dictionary

---

##  Power BI 

- **DAX Measures**:
  - `Average Ridership`
  - `Ridership Per Stop`
  - `Route with Maximum Ridership`
- **Calculated Columns**:
  - Route Display Name, etc.
- **Data Modeling**:
  - Star schema with fact and dimension tables

---

##  Tools & Technologies

- Power BI  
- DAX (Data Analysis Expressions)  
- Data Modeling  
- Map Visualizations  

---

##  Project Sponsor

**IndyGo** – Indianapolis Public Transportation Corporation

---


