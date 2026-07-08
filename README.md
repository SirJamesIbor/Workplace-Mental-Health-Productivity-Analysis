# Workplace-Mental-Health-And-Productivity-Analysis
Data analysis exploring how employee mental health status, workplace support, and work model (remote/hybrid/on-site) relates to workplace productivity and absenteeism.

## Problem Statement

Organizations are increasingly aware that employee mental health affect business productivity, however only few analysis quantify exactly to what percentage of effect it thus has. This project therefore investigate whether employee mental health status, workplace support, and work model (remote/hybrid/on-site) measurably affect productivity and absenteeism in the workplace - turning an HR/wellbeing conversation into  a data-backed case as the WHO estimates that stressors such as depression and anxiety cost the global economy $1 trillion per year in lost productivity.

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

1. *That employee mental health status is strongly linked to workplace productivity*. Employees with no reported mental health condition had the highest average productivity score (7.24), while those reporting burnout, depression, and multiple conditions recorded the lowest on productivity (4.96 - 4.98 avg). **This suggests burnout,and multiple health conditions carry a distinct, more severe productivity cost than well-managed health conditions**.
2. Similarly, findings revealed that Burnout (18.16%), Depression (18.05) and Multiple Conditions reported (18.32%) had the highest records of absenteeism days (18) per year on average, compared to 3 days/year for employees with no reported condition - **posing a 6x difference that directly translate to operational cost.**
3. Employer support level showed little or no-effect on productivity, as scores stayed within a narrow 6.42 - 6.46 band regardless of whether employer support was rated Poor, Average, Good, or Excellent. This is a counter-intuitive finding worth flagging to stakeholders to suggest current "Support Level" may be helping wellbeing without addressing the specific drivers of burnout and absenteeism.
4. From my analysis, the average productivity scores across the three work modes was the same, indicating that work mode has no significant influence on productivity. This suggests that work mode alone may not be a major determinant of productivity.
Furthermore, despite the similar productivity levels across the work modes, our analysis shows that the Remote Work mode has a relatively higher work-life balance score and a lower burnout risk score compared to the other work modes.

## Dashboard

<img width="722" height="478" alt="dasboard preview" src="https://github.com/user-attachments/assets/3db324a9-8d54-4357-92f8-e4438db025f7" />

## What I would Explore Next

My nest-steps thinking











