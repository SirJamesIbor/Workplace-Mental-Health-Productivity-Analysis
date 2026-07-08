# Workplace-Mental-Health-Productivity-Analysis
Organizations are increasingly aware that employee mental health affect business productivity, but few analysis quantify exactly to what percentage of effect it thus has. This project therefore investigate whether employee mental health status, workplace support, and work model (remote/hybrid/on-site) measurably affect productivity and absenteeism in the workplace - turning an HR/wellbeing conversation into  a data-backed case.

## Problem Statement

The WHO estimates that depression and anxiety cost the global economy $1 trillion per year in lost productivity, yet many organizations lack structured mental health support.

## Data Source
**Kaggle:** 10,000 employee records across 20 countries and 17 industries (2020-2025) covering 34 variables - 

Mental health conditions and diagnosis status

Productivity, burnout risk, and work-life balance scores

Absenteeism days per year

Work model, and employee support level

## Method

**Data Cleaning (Excel/Power-BI)**
- Audited 10,000 records with 34 columns for duplicates, whitespace issues, and logic inconsistencies (0 found)

- Standardized all column names (lowercase, underscore-separated) for consistency

- Identified and resolved 12,012 missing values across 4 fields, using context-appropriate fills (e.g. "No Condition reported", Not      Applicable") rather than blanket deletion - preserving sample size and avoiding bias

- Verified zero remaining missing values before analysis

**Analysis (Pivot Table)**
- Built 4 analysis views (Q1-Q4) isolating the relationship between mental health status, employer support, work model, and productivity/absenteeism outcomes
  
- Cross-referenced burnout risks and absenteeism by condition to separate correlation from noise

**Visualization**
- Designed a single page executive dashboard combining KPIs summary cards with 3 comparative bar charts


**Excel/Power Bi:** Data cleaning (12,012 missing values handled), pivot tables, visualization and dashboard design

## Key Findings

1. The findings indicates that employee mental health status is strongly linked to workplace productivity. Employees with no recorded mental health condition had the highest average productivity score
2. Findings revealed that Burnout (18.16%), Depression (18.05) and Multiple Mental Health Conditions (18.32%) are positively associated with absenteeism, versus 3.1% for employees with no reported condition - a 6x difference that directly translate to operational cost. 
3. From my analysis, the average productivity scores across the three work modes was the same, indicating that work mode has no significant influence on productivity. This suggests that work mode alone may not be a major determinant of productivity.
Furthermore, despite the similar productivity levels across the work modes, our analysis shows that the Remote Work mode has a relatively higher work-life balance score and a lower burnout risk score compared to the other work modes.

## Dashboard

<img width="722" height="478" alt="dasboard preview" src="https://github.com/user-attachments/assets/3db324a9-8d54-4357-92f8-e4438db025f7" />

## What I would Explore Next

My nest-steps thinking











