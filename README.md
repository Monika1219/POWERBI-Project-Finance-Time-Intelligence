# 📊 Finance Report with Time Intelligence

## Overview
This project demonstrates advanced Power BI development using the Financial Sample dataset. It focuses on:

- Time‑intelligence DAX
- Year‑over‑year variance analysis
- Rolling 12‑month metrics
- KPI‑driven reporting
- Clean dashboard layout
- Validation tables for accuracy

The report contains two pages: Main Report and Tables Page.

## Data Model

### Tables
- **Fact Finance** — sales, profit, date, segment, country
- **Date Table** — continuous calendar with Year, Quarter, Month, Year‑Month
- (Optional) Segment, Country, Product dimensions

### Relationships
- Date[Date] → Fact Finance[Date] (1:*)
- Date table marked as the official date table
- Screenshots available in /DataModel.

## DAX Measures

Key measures include:

- Total Sales
- Total Profit
- Profit Margin %
- Sales MTD / QTD / YTD
- Sales LY
- Sales Var vs LY / %
- Sales Rolling 12M
- Avg Sales Last 12M
- Forecast Sales
- Actual + Forecast

Full DAX code is included in /DAX/AllMeasures.dax.

## Report Pages

### Main Report
- KPI cards
- Total Sales by Date
- Rolling 12M vs Total Sales
- Sales by Segment
- Sales by Country
- Navigation buttons
- Filters: Year, Country, Segment

### Tables Page
- Time‑intelligence validation table (MTD, QTD, YTD)
- YoY variance table
- Filters: Year, Country, Segment

## Screenshots

Located in /Screenshots:

- Main Report
- Tables Page
- Total Sales by Date
- Rolling 12M vs Total Sales
- Sales by Segment
- Sales by Country
- Time Intelligence Table
- YoY Variance Table
- KPI cards
- Filters & navigation

## Repository Structure

### Code
```
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
```

## Summary

This project demonstrates:

- Professional Power BI dashboard design
- Advanced time‑intelligence DAX
- Rolling metrics and YoY variance
- Clean star‑schema modelling
- KPI‑driven reporting
- Validation tables for accuracy
- Clear navigation and UX
