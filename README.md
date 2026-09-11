# HR-Attrition-Analysis
An interactive HR Attrition Analysis Dashboard built with Tableau to analyze employee turnover, compensation alignment, workforce satisfaction, demographics, and department-level retention metrics. Features actionable insights to improve employee retention.  
# HR Attrition Analysis Dashboard

[![Power BI](https://img.shields.io/badge/Power_BI-F2C94C?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Data Analytics](https://img.shields.io/badge/Data_Analytics-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)](https://azure.microsoft.com/)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)]()

An interactive **HR Attrition Analysis Dashboard** designed to evaluate employee turnover, compensation alignment, satisfaction levels, demographics, and department-level retention metrics.

---

## Table of Contents
1. [Project Overview](#-project-overview)
2. [Key Performance Indicators (KPIs)](#-key-performance-indicators-kpis)
3. [Dashboard Breakdown](#-dashboard-breakdown)
4. [Key Insights & Findings](#-key-insights--findings)
5. [Actionable Recommendations](#-actionable-recommendations)
6. [Tools & Technologies Used](#-tools--technologies-used)

---

## Project Overview

Employee attrition poses significant costs to organizations in recruitment, onboarding, and lost productivity. This dashboard provides human resources leaders with dynamic insights into workforce stability, identifying root causes behind attrition across demographics, roles, compensation tiers, and job satisfaction metrics.

---

## Key Performance Indicators (KPIs)

| Metric | Value | Target / Benchmark | Description |
| :--- | :---: | :---: | :--- |
| **Total Employees** | **1,480** | — | Total workforce count evaluated |
| **Avg Monthly Income** | **$6,505** | Baseline Average | Organization-wide mean monthly salary |
| **Job Satisfaction Rate** | **61%** | > 75% | Proportion of satisfied employees |
| **Attrition Rate** | **16%** | < 10% | Overall employee turnover rate |
| **Promotion Rate** | **40%** | Growth Benchmark | Proportion of employees receiving career progression |

---

## Dashboard Breakdown

### 1. Attrition Rate according to AVG Salaries
* Compares average monthly income across **Job Roles** against the company average income benchmark line (~$6.5K).
* Displays salary categorization (**Above** vs. **Below** average) alongside corresponding attrition percentages per role:
  * **Sales Representatives:** Highest attrition at **39%** (salaries below average).
  * **Laboratory Technicians / Human Resources / Healthcare Representatives:** High attrition (**23% - 24%**) associated with below-average salaries.
  * **Managers & Research Directors:** Minimal attrition (**3% - 5%**) tied to above-average salaries ($15K - $20K range).

### 2. Attrition Rate by Gender for Different Age Groups
* **18–25:** **42% Female** vs. **33% Male** attrition (Highest overall turnover group).
* **26–35:** **19% Female** vs. **19% Male** attrition.
* **36–45:** **7% Female** vs. **11% Male** attrition.
* **46–55:** **7% Female** vs. **16% Male** attrition.
* **55+:** **14% Female** vs. **19% Male** attrition.

### 3. Attrition by Marital Status
* **Single:** **50%** of total turnover (Highest risk category).
* **Married:** **35%** of total turnover.
* **Divorced:** **14%** of total turnover.

### 4. Satisfaction Rates for Each Job Role (Matrix / Heatmap)
Evaluates job satisfaction scores (Levels 1 to 4) across key roles:
* **High satisfaction volume (Score 3–4):** Sales Executives, Research Scientists, Laboratory Technicians.
* **Low satisfaction count (Score 1–2):** High risk identified among lower-paid operational roles like Sales Representatives and HR personnel.

### 5. Attrition by Department
* **Sales:** **21% Attrition**
* **Human Resources:** **19% Attrition**
* **Research & Development:** **14% Attrition** (Largest total employee count)

---

## Key Insights & Findings

1. **Compensation & Turnover Correlation:** Roles earning below the average monthly income ($6,505), particularly **Sales Representatives (39%)** and **Laboratory Technicians (24%)**, experience significantly higher turnover compared to executive roles (3–5%).
2. **Early-Career Vulnerability:** The **18–25 age group** shows critical attrition rates, especially among **Females (42%)** and **Males (33%)**.
3. **Marital Status Impact:** **Single employees** constitute **50%** of total organizational departures, indicating potential mobility or retention challenges in early-to-mid career stages.
4. **Departmental Risk:** The **Sales Department** has the highest department-level attrition at **21%**, followed closely by **Human Resources (19%)**.

---

## Actionable Recommendations

* **Compensation Realignment:** Conduct salary benchmarking for **Sales Representatives** and **Laboratory Technicians** to bring base pay closer to market standards.
* **Early-Career Mentorship & Retention:** Implement career progression pathways and onboarding support specifically targeting younger demographics (18–25 age group).
* **Sales Department Interventions:** Review commission structures, workload distributions, and sales targets to reduce burnout in the Sales team.
* **Targeted HR Surveys:** Focus stay-interviews on single employees and roles reporting low satisfaction scores (Satisfaction Level 1 & 2).

---

## Tools & Technologies Used

* **Power BI Desktop:** Data Modeling, Visualizations, Heatmaps, and Custom Layouts.
* **DAX (Data Analysis Expressions):** Custom measures for Attrition Rate, Average Salaries, Satisfaction Metrics, and Age Group segmentations.
* **Power Query (ETL):** Data cleaning, transformations, conditional columns, and field grouping.

---

