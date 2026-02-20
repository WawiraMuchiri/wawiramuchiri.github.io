---
title: "HR Analytics Dashboard: Data Visualization using Tableau"
date: 2026-02-21
categories: [Data, Tableau, HR Analytics]
tags: [Tableau, HR, Business Intelligence, Data Visualization]
layout: post
comments: true
toc: true
---

# HR Analytics Dashboard – Data Visualization using Tableau

**Project Overview:**  
This project showcases an **interactive HR dashboard** built in Tableau using a dataset of **8,950 employee records**. The dashboard delivers both **executive-level workforce insights** and **detailed employee-level analysis** within a single analytical framework.  

**Dashboard Link:** [View Tableau Dashboard](https://drive.google.com/file/d/1b-z4wh2wD69GBLEFpTiAjnUnK9ut2SB4/view?usp=sharing)  

---

## Table of Contents
1. [Introduction](#introduction)  
2. [Data Loading and Preparation](#data-loading-and-preparation)  
   - 2.1 [Data Loading](#data-loading)  
   - 2.2 [Data Cleaning and Transformation](#data-cleaning-and-transformation)  
3. [Calculated Fields and Business Logic](#calculated-fields-and-business-logic)  
4. [Dashboard Design and Visualization](#dashboard-design-and-visualization)  
   - 4.1 [Main Summary Dashboard](#main-summary-dashboard)  
   - 4.2 [HR Detailed Employee Records Dashboard](#hr-detailed-employee-records-dashboard)  
5. [Publishing and Sharing](#publishing-and-sharing)  
6. [Conclusion](#conclusion)  

---

## Introduction
Business Intelligence is essential for modern HR management. It enables organizations to make strategic workforce decisions using accurate, structured, and timely data.  

The dashboard integrates **Overview, Demographics, Income Analysis, and Employee Records**, providing clear visibility into workforce composition, hiring trends, salary structures, and performance patterns. It supports informed HR decision-making through structured, data-driven insights.

---

## Data Loading and Preparation

### 2.1 Data Loading
- Imported the HR dataset into Tableau.  
- Verified field names, data types, and record counts.  
- Dataset confirmed at **8,950 records**.  

*Screenshot 1 – Tableau Data Source showing dataset loaded.*

### 2.2 Data Cleaning and Transformation
- Validated field data types: dates, numeric measures, and dimensions.  
- Formatted `Hire Date`, `Termination Date`, and `Birthdate` as date fields.  
- Configured `Salary` as numeric.  
- Organized geographic fields; used Tableau’s latitude/longitude for location analysis.  

*Screenshot 2 – Data Pane showing field validation and structure.*

---

## Calculated Fields and Business Logic
Calculated fields were developed to generate key workforce metrics:  

- **Age** from Birthdate using `DATEDIFF`.  
- **Total Hired Employees**: `COUNT(Employee ID)`.  
- **Total Active Employees**: Conditional on termination status.  
- **Total Terminated Employees**: Conditional aggregation.  
- **Employee Status**: Active vs Terminated.  
- **Age Groups** for demographic segmentation.  
- **Hire Year & Termination Year** for trend analysis.  

*Screenshot 3 – Tableau Data Pane showing calculated fields.*

---

## Dashboard Design and Visualization

### 4.1 Main Summary Dashboard
The **Main Summary Dashboard** delivers executive-level HR insights in one interactive interface:

**Workforce Overview:**  
- Total Hired: 8,950  
- Active Employees: 7,984  
- Terminated Employees: 966  
- Operations, Sales, and Customer Service are largest segments.  
- Headquarters: New York; other states show structured presence.  

**Demographics Analysis:**  
- Gender distribution: balanced, slight male majority.  
- Age: 35–44 is largest group.  
- Education: Bachelors dominate; Masters/PhD align with higher performance.  

**Income Analysis:**  
- Salary rises with education and age.  
- Senior roles cluster in higher pay brackets.  
- Compensation structured by role, seniority, and experience.  

**Key Insight:**  
This dashboard enables HR leadership to monitor workforce trends, demographic composition, and compensation alignment at a glance.

*Screenshot 4 – Main Summary Dashboard.*

---

### 4.2 HR Detailed Employee Records Dashboard
The **Detailed Employee Records Dashboard** enables drill-down analysis of individual employee data:

**Workforce Structure:**  
- Employees distributed across Operations, Sales, Finance, Marketing, Customer Service.  
- Mid-level qualifications dominate.  

**Tenure and Retention:**  
- Employment length: 3–10 years; strong retention among hires 2016–2019.  

**Salary and Role Alignment:**  
- Higher compensation aligns with managerial/analyst roles.  
- Entry/support roles have lower salary ranges.  

**Geographic Distribution:**  
- Concentrated in New York; branch offices support operational needs.  

**Strategic Value:**  
- Allows HR leadership to evaluate individual employee profiles, tenure trends, compensation alignment, and workforce filtering.  
- Links high-level insights from the Main Dashboard with operational, employee-level data.

*Screenshot 5 – Detailed Employee Records Dashboard.*

---

## Publishing and Sharing
- Dashboard published to **Tableau Public** for secure, cloud-based access.  
- Fully interactive; stakeholders can explore data without Tableau Desktop.  
- Incorporated into professional portfolio to demonstrate HR analytics expertise.  

**Dashboard Link:** [View Tableau Dashboard](https://drive.google.com/file/d/1b-z4wh2wD69GBLEFpTiAjnUnK9ut2SB4/view?usp=sharing)  

---

## Conclusion
This HR analytics project demonstrates the ability to:

- Load and structure a comprehensive HR dataset.  
- Develop calculated fields aligned with workforce metrics.  
- Design an **interactive Main Summary Dashboard** and a **Detailed Employee Records Dashboard**.  
- Deliver actionable insights to support strategic HR decision-making, workforce planning, and compensation evaluation.  

The dashboards illustrate the translation of complex HR data into clear, structured, and actionable business intelligence.
