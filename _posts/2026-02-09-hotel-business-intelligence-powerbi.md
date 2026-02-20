---
title: "Hotel Performance Dashboard – Power BI Business Intelligence Project"
date: 2026-02-21
categories: [Business Intelligence, Power BI]
tags: [powerbi, dax, data-modeling, analytics, star-schema]
image: /assets/images/hotel-dashboard-overview.png
---

## 📌 Project Overview

This project applies Business Intelligence techniques using Power BI to analyze hotel management data and deliver an interactive dashboard that supports operational and strategic decision-making.

The objective was to transform structured hospitality datasets into clear, decision-ready insights on revenue performance, occupancy trends, pricing effectiveness, and room utilization.

---

## 🧩 Business Problem

Hotel management teams require visibility into:

- Occupancy trends
- Revenue drivers
- Seasonal demand patterns
- Room category performance
- Pricing effectiveness (ADR & RevPAR)

Without structured analytics, decisions become reactive rather than data-driven.

This project addresses that gap by implementing a structured BI workflow using Power BI.

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
- Removed irrelevant columns
- Renamed fields for clarity and consistency

All transformations ensured clean, analysis-ready data aligned with modeling best practices.

---

## 🏗 Data Modeling – Star Schema

Implemented a star schema design:

- Central fact table
- One-to-many relationships to dimension tables (date, room category)
- Optimized for performance and analytical scalability

This structure improved query efficiency and enabled reliable KPI calculations.

---

## 📊 DAX Measures & KPI Development

Developed calculated columns and measures using DAX, including:

- Total Revenue
- Occupancy Rate
- ADR (Average Daily Rate)
- RevPAR
- Week-over-Week Change Metrics
- Weekend vs Weekday classification logic

These dynamic measures enabled time-based performance tracking and comparative analysis.

---

## 📊 Final Dashboard

![Hotel Performance Dashboard](/assets/images/hotel-dashboard-overview.png)

The dashboard integrates:

- KPI Cards for revenue, ADR, RevPAR, and occupancy
- Revenue and occupancy trend analysis
- Room category comparison visuals
- Interactive slicers (city, room class, time period)

---

## 🔎 Key Business Insights

- Clear seasonal demand fluctuations across the timeline
- Certain room categories consistently outperform others
- Revenue performance is influenced by pricing strategy, not occupancy alone
- Low-demand periods reveal room underutilization opportunities
- Time-based performance monitoring supports proactive decision-making

---

## 🛠 Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Star Schema Data Modeling

---

## 🎯 Outcome

This project demonstrates:

- Structured data modeling skills
- DAX proficiency
- Business-focused analytical thinking
- Dashboard design for executive-level decision support

It reflects my ability to transform raw hospitality data into actionable Business Intelligence insights.
