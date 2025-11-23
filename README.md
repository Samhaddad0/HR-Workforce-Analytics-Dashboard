📊 HR Attendance Analytics

-Supported an HR department by uncovering Work from Home(WFH) vs. Work from Office(WFO) preferences, monitoring sick leave patterns, delivering insights to optimize workspace planning, and reduce costs.


📁 Project Overview

-This project simulates a real HR analytics use case where employee attendance data across multiple months is analyzed to uncover work-from-home patterns, sick leave trends, presence rates, and weekly seasonality.
-The goal was to build a fully automated Power BI dashboard that HR can use to monitor workforce availability, optimize office capacity planning, and explore cost saving oppertunites.

📊 Dataset Description

| Field         | Description                                           |
| ------------- | ----------------------------------------------------- |
| Employee Code | Unique ID for each employee (anonymized)              |
| Employee Name | Fake names – but **real attendance data**             |
| Date Columns  | Each day of the month                                 |
| Cell Values   | Attendance codes: P, WFH, HWFH, SL, HSL, HO, WO, etc. |

| Code | Meaning                   |
| ---- | ------------------------- |
| P    | Present                   |
| WFH  | Work From Home (Full Day) |
| HWFH | Half Work From Home       |
| SL   | Sick Leave                |
| HSL  | Half Sick Leave           |
| HO   | Holiday Off               |
| WO   | Weekly Off                |
| LWP  | Leave Without Pay         |


🎯 Business Questions / Objectives

Primary Objectives:

-What is the overall presence % by month and employee?

-What are the work-from-home trends? Are certain days preferred?

-Can we detect early signs of health issues or COVID spikes through sick leave patterns?

-Which day of the week has the lowest presence?


🧰 Tools & Technologies Used

| Category      | Tools                                  |
| ------------- | -------------------------------------- |
| Data Source   | Excel                                  |
| Data Cleaning | Power Query (Power BI)                 |
| Data Modeling | DAX (Measures & Calculated Columns)    |
| Dashboarding  | Power BI Desktop                       |
| Automation    | SharePoint / Power BI Service (future) |


🔄 Methodology & Workflow

This project followed an end-to-end analytics lifecycle commonly used in real business environments:

1. Requirement Gathering

Discussed HR pain points with stakeholders

Defined key objectives: presence tracking, WFH analysis, sick leave monitoring, and operational cost optimization

2. Data Extraction & Loading

Imported raw Excel attendance data into Power BI

Used Power Query to prepare and structure the dataset

3. Data Transformation (ETL)

Unpivoted wide-format data into row-level records

Cleaned null values and standardized column formats

Created derived fields (Month, Day of Week, Category Codes)

Used DAX to calculate key metrics such as Presence %, WFH %, Sick Leave %, and Employee Performance

4. Dashboard Development

Designed interactive visuals with slicers, KPIs, table views, and trend charts

Prioritized stakeholder-friendly layout (top-left KPIs, drill-down views, trend analysis)





