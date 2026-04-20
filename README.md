📊 Finance Report with Time Intelligence (Power BI Developer Project)
📌 Overview
This project demonstrates advanced Power BI development using the Financial Sample dataset.
It focuses on time intelligence, variance analysis, rolling metrics, and a clean, professional dashboard layout.

The report contains two pages:

Main Report – KPIs, time‑series charts, and segment/country analysis

Tables – detailed MTD/QTD/YTD validation tables and YoY variance table

This project is designed to showcase real Power BI developer skills for your portfolio.

🧱 Data Model
Tables
Fact Finance – sales, profit, date, segment, country

Date – continuous date table with Year, Quarter, Month, Year‑Month

(Optional) Dimension tables for Segment, Country, Product

Relationships
Date[Date] → Fact Finance[Date] (1:*)

Single‑direction

Date table marked as official Date table

Screenshots included in /DataModel.

🧮 DAX Measures
Base Measures
Total Sales

Total Profit

Profit Margin %

Time Intelligence
Sales MTD

Sales QTD

Sales YTD

Sales LY

Sales Var vs LY

Sales Var vs LY %

Sales Rolling 12M

Forecasting (optional)
Avg Sales Last 12M

Forecast Sales

Actual + Forecast

All DAX code is included in /DAX/AllMeasures.dax.

📊 Report Pages
1. Main Report
This page provides a complete financial overview with KPIs, time‑series analysis, and breakdowns.

Filters
Year

Country

Segment

Navigation
Main Report (active)

Tables (button)

KPIs
Total Sales

Sales Var vs LY %

Sales Rolling 12M

Sales LY

Visuals
Total Sales by Date (line chart)

Rolling 12M vs Total Sales (dual line chart)

Total Sales & Var vs LY % by Segment (bar chart)

Total Sales by Country (bar chart)

2. Tables Page
This page validates all time‑intelligence logic using detailed tables.

Filters
Year

Country

Segment

Navigation
Main Report

Tables (active)

Visuals
Table 1 — Time Intelligence Validation
Columns:

Year

Total Sales

Sales MTD

Sales QTD

Sales YTD

Breakdown:

Year → Quarter → Month

Confirms correct MTD/QTD/YTD accumulation

Table 2 — YoY Variance
Columns:

Year‑Month

Total Sales

Sales Var vs LY

Shows month‑over‑month YoY comparison.

📸 Screenshots Included
Inside /Screenshots:

Main Report

Tables Page

Total Sales by Date

Rolling 12M vs Total Sales

Sales by Segment

Sales by Country

Time Intelligence Table

YoY Variance Table

KPI cards

Filters & navigation buttons

Inside /DataModel:

Data model

Relationships

Date table

📁 Repository Structure
Code
/DataModel
    Model.png
    Relationships.png
    DateTable.png

/DAX
    AllMeasures.dax

/Screenshots
    MainReport.png
    TablesPage.png
    SalesByDate.png
    Rolling12M.png
    SalesBySegment.png
    SalesByCountry.png
    TimeIntelligenceTable.png
    YoYVarianceTable.png

/PowerBI
    Finance_TimeIntelligence.pbix

README.md
🏁 Summary
This project demonstrates:

Professional Power BI dashboard design

Advanced time‑intelligence DAX

Rolling metrics and YoY variance

Clean star‑schema modelling

KPI‑driven executive reporting

Validation tables for accuracy

Clear navigation and UX