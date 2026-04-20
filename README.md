Finance Report with Time Intelligence
📌 Overview
This project demonstrates advanced Power BI development using the Financial Sample dataset.

It includes:

Time‑intelligence DAX

Year‑over‑year variance analysis

Rolling 12‑month metrics

KPI‑driven reporting

Clean dashboard layout

Validation tables for accuracy

The report contains two pages:

Main Report

Tables Page

📂 Data Model
Tables
Fact Finance – sales, profit, date, segment, country

Date Table – continuous calendar with Year, Quarter, Month, Year‑Month

(Optional) Dimension tables for Segment, Country, Product

Relationships
Date[Date] → Fact Finance[Date] (1:*)
This is the core relationship driving the model.

Screenshots included in /DataModel.

🧮 DAX Measures
Total Sales

Total Profit

Profit Margin %

Sales MTD

Sales QTD

Sales YTD

Sales LY

Sales Var vs LY

Sales Var vs LY %

Sales Rolling 12M

Avg Sales Last 12M

Forecast Sales

Actual + Forecast

(Full DAX code included in /DAX/AllMeasures.dax)

📊 Report Pages
Main Report
KPI cards

Total Sales by Date

Rolling 12M vs Total Sales

Sales by Segment

Sales by Country

Navigation buttons

Filters: Year, Country, Segment

Tables Page
Time‑intelligence validation table (MTD, QTD, YTD)

YoY variance table

Filters: Year, Country, Segment

📸 Screenshots
Include:

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

KPI‑driven reporting

Validation tables for accuracy

Clear navigation and UX
