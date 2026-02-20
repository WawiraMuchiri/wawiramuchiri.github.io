---
title: "Hotel Performance Dashboard – Power BI Business Intelligence Project"
date: 2026-02-09
categories: [Business Intelligence, Power BI]
tags: [powerbi, dax, data-modeling, analytics, star-schema]
image: /assets/images/hotel-dashboard-overview.png
---

## 📌 Project Overview

This project applies Business Intelligence techniques using Power BI to analyze hotel management data and deliver an interactive dashboard that supports operational and strategic decision-making.

The objective was to transform structured hospitality datasets into clear, decision-ready insights on revenue performance, occupancy trends, pricing effectiveness, and room utilization.

---

## 🧩 Business Problem

Hotel management teams require structured visibility into:

- Occupancy trends  
- Revenue drivers  
- Seasonal demand fluctuations  
- Room category performance  
- Pricing effectiveness (ADR & RevPAR)

Without consolidated analytics, decisions become reactive rather than data-driven. This project addresses that gap through structured modeling and KPI development.

---

## 🔄 Data Preparation & Transformation

Using Power Query Editor:

- Imported fact and dimension tables:
  - `fact_bookings`
  - `fact_aggregated_bookings`
  - `dim_date`
  - `dim_rooms`
- Corrected data types  
- Promoted headers  
- Removed unnecessary columns  
- Renamed fields for clarity and consistency  

These transformations ensured analysis-ready data aligned with modeling best practices.

---

## 🏗 Data Modeling – Star Schema

Implemented a star schema design:

- Central fact table  
- One-to-many relationships to dimension tables (date, room category)  
- Optimized structure for performance and scalability  

This model enabled efficient KPI computation and reliable analytical outputs.

---

## 📊 DAX Measures & KPI Development

Developed calculated columns and measures using DAX, including:

- Total Revenue  
- Occupancy Rate  
- ADR (Average Daily Rate)  
- RevPAR  
- Week-over-Week performance metrics  
- Weekend vs Weekday classification logic  

These dynamic measures enabled time-based analysis and comparative performance tracking.

---

## 📊 Dashboard Design & Executive Insights

The dashboard provides executive-level visibility into hotel performance by combining financial and operational KPIs in a single decision-ready interface.

It enables stakeholders to:

- Monitor revenue, ADR, RevPAR, and occupancy in real time  
- Identify seasonal demand shifts and revenue fluctuations  
- Compare room category profitability and utilization  
- Analyze performance across cities, time periods, and room classes using interactive filters  

The design prioritizes clarity, comparability, and actionable insight rather than visual complexity.

---

## 🔎 Key Business Insights

- Seasonal demand fluctuations are clearly visible across the timeline  
- Certain room categories consistently outperform others in revenue contribution  
- Revenue performance is influenced by pricing strategy, not occupancy alone  
- Low-demand cycles reveal opportunities for targeted promotional strategies  
- Time-based monitoring supports proactive operational decision-making  

---

## 🛠 Tools & Technologies

- Power BI Desktop  
- Power Query  
- DAX  
- Star Schema Data Modeling  

---

## 🎯 Outcome

This project demonstrates structured data modeling, advanced DAX application, and business-focused dashboard design.

It reflects my ability to transform raw hospitality data into actionable Business Intelligence insights that support informed decision-making.
