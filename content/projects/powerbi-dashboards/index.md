---
title: "Business Intelligence Dashboards with Power BI (Northwind)"
date: 2026-01-22
summary: "Power BI dashboards built on a star-schema model for executive reporting, product analytics, and employee performance analysis."
tags: ["Power BI", "Business Intelligence", "Data Modeling", "DAX", "Dashboard"]
authors: ["jiayi-shi"]
featured: true
---

## What I built
A suite of **Power BI dashboards** using the **Northwind** dataset:
- **Executive Summary** (KPIs + trends)
- **Product Report** (category/product performance)
- **Employee Report** (employee-level contribution analysis)

## Data model
- Fact: Orders, Order Details  
- Dimensions: Products, Categories, Customers, Employees, Region/Country  
- Star-schema design for scalable slicing and drill-down

## KPI / Measures
- Revenue, No. of Orders, and other summary KPIs
- Drill-down by region, category, product, and time
- Cross-filtering and slicers for interactivity

## Screenshots
![Executive Summary](executive-summary.png)

![Product Report](product-report.png)

![Employee Report](employee-report.png)
