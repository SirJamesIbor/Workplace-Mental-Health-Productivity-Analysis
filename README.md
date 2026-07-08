# Workplace-Mental-Health-And-Productivity-Analysis
Data analysis exploring how employee mental health status, workplace support, and work model (remote/hybrid/on-site) relates to workplace productivity and absenteeism.

## Problem Statement

Organizations are increasingly aware that employee mental health affect business productivity, however only few analysis quantify exactly to what percentage of effect it thus has. This project therefore investigate whether employee mental health status, workplace support, and work model (remote/hybrid/on-site) measurably affect productivity and absenteeism in the workplace - turning an HR/wellbeing conversation into  a data-backed case as the WHO estimates that stressors such as depression and anxiety cost the global economy $1 trillion per year in lost productivity.

## Data Source
**Kaggle:** 10,000 employee records across 20 countries and 17 industries (2020-2025) covering 34 variables - 

- Mental health conditions and diagnosis status

- Productivity, burnout risk, and work-life balance scores

- Absenteeism days per year

- Work model, and employee support level

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
- **Slicer Interactivity:** Dashboard incorporates interactive slicers, enabling stakeholders to dynamically filter by work mode and mental health condition, supporting self-servive exploration beyond the static dashboard view. 

**Excel/Power Bi:** Data cleaning (12,012 missing values handled), pivot tables, visualization and dashboard design

## Key Findings

1. That employee mental health status is strongly linked to workplace productivity. Employees with no reported mental health condition had the highest average productivity score (7.24), while those reporting burnout, depression, and multiple conditions recorded the lowest on productivity (4.96 - 4.98 avg). *This suggests burnout,and multiple health conditions carry a distinct, more severe productivity cost than well-managed health conditions*.
2. Similarly, findings revealed that Burnout (18.16%), Depression (18.05) and Multiple Conditions reported (18.32%) had the highest records of absenteeism days (18) per year on average, compared to 3 days/year for employees with no reported condition - *posing a 6x difference that directly translate to operational cost.*
3. Employer support level showed little or no-effect on productivity, as scores stayed within a narrow 6.42 - 6.46 band regardless of whether employer support was rated Poor, Average, Good, or Excellent. This is a counter-intuitive finding worth flagging to stakeholders to suggest *current "Support Level" may be helping wellbeing without addressing the specific drivers of burnout and absenteeism.*
4. The average productivity scores across the three work modes (Remote/Hybrid/On-site) was the same (6.4), indicating that work mode has no significant influence on productivity. Furthermore, Remote employees recorded the best work-life balance (6.9) and lowest Burnout risk (3.8) compared (6.2) and (4.1) for the other work modes respectively. *This suggest remote flexibility is a low-cost lever for wellbeing with no productivity trade-off.*

## Dashboard
<img width="451" height="465" alt="dasboardpreview" src="https://github.com/user-attachments/assets/518e36f2-b43e-4684-b9bf-ab6e361d4a29" />

## What I would Explore Next

- **Statistical significance testing** using ANOVA or t-tests to confirm whether the productivity differences by condition and support level are statistically meaningful , and not just descriptive averages
- **Segment the "Employer support" findings by industry or company size** - it is possible support programs work well in some contexts and not others, and the aggregate average is masking it.
- **Time-based trend analysis** - with 5 years of data (2020 - 2025), tracking whether burnout/productivity patterns shifted post-pandemic as remote work adoption changed globally.











