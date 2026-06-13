# Healthcare Operations Performance Analysis

An interactive Power BI dashboard built on SQL-based extraction and transformation pipelines, designed to convert 50,000+ raw hospital records into governed, decision-ready KPIs for management — covering patient operations, doctor performance, financial metrics, and staff utilization.

<img width="1441" height="819" alt="Hospital Dashboard Overview" src="https://github.com/user-attachments/assets/f3b822cc-4736-4801-8110-aa2f2e13ea3c" />

---

## Why This Project

Hospitals generate large volumes of data across patients, doctors, finance, and staff — but raw data alone doesn't drive decisions. This project builds a full pipeline from **data extraction and reconciliation to executive-facing dashboards**, so hospital management can move from "what happened" to "what should we do next" without manually digging through spreadsheets.

The focus throughout was on **data quality and reconciliation first** — consolidating records from multiple departments, applying validation checks, and only then layering on visualization — mirroring how operational BI is delivered in real enterprise settings.

---

## Problem Statement

Hospitals generate large volumes of data across departments such as patients, doctors, finance, and staff. The challenge is to convert this raw, siloed data into actionable insights that help management:

- Improve patient care
- Optimize doctor workload
- Track revenue and expenses
- Monitor staff efficiency

---

## Objectives

- Consolidate and clean 50,000+ patient, financial, and operational records into analytics-ready datasets
- Apply CTEs, window functions, and reconciliation checks to ensure data quality before analysis
- Build KPI-driven dashboards for department-wise and hospital-wide performance
- Enable quick, cross-functional decision-making through interactive views
- Surface critical data gaps and operational bottlenecks to inform resource allocation

---

## Tools & Technologies

| Category | Tools |
|----------|-------|
| **Data Extraction & Transformation** | SQL (CTEs, window functions), Power Query |
| **Data Quality** | Reconciliation checks, validation queries |
| **Analytics & Visualization** | Power BI, DAX, Excel |
| **Layout & UI Planning** | Figma |

---

## Pipeline & Dashboard Structure

The project follows a layered approach: extraction → transformation/reconciliation → modeling → visualization.

### 1. Data Extraction & Transformation
SQL-based pipelines consolidate raw records from patient, financial, and operational sources. CTEs and window functions are used for running totals, department-wise aggregations, and trend calculations, with reconciliation checks applied to catch inconsistencies before the data reaches the dashboard layer.

### 2. Overview Dashboard
High-level hospital performance at a glance — admission/discharge trends and overall KPIs for management review.

<img width="1441" height="819" alt="Overview Dashboard" src="https://github.com/user-attachments/assets/91245dfb-ff1d-4e71-bcb2-556110ca39d9" />

### 3. Patient Analysis
- Patient demographics
- Disease-wise distribution
- Admission trends over time

### 4. Doctor Analysis
- Doctor workload
- Department-wise doctor availability
- Performance metrics

### 5. Finance Dashboard
- Revenue vs. expenses
- Department-wise revenue
- Monthly and yearly financial trends

### 6. Staff Analysis
- Staff count by role
- Department allocation
- Utilization insights

---

## Key Insights

- Identified high-traffic departments impacting overall hospital load
- Detected revenue-generating departments vs. cost-heavy areas
- Analyzed patient inflow patterns to support better resource planning
- Improved visibility into doctor and staff utilization across departments
- Surfaced data quality gaps that, once resolved, improved reporting accuracy for stakeholder-facing KPIs

---

## Impact

By combining SQL-based reconciliation with Power BI's KPI dashboards, this project reduced the manual effort needed to produce stakeholder reports and gave hospital management a single, trustworthy view of operations — cutting reporting turnaround time and enabling faster, data-driven capacity planning decisions.

---

## What I'd Build Next

- Automate the SQL extraction layer to refresh dashboards on a schedule rather than manual updates
- Add anomaly detection on key metrics (e.g. sudden revenue drops, abnormal admission spikes)
- Extend reconciliation checks into a reusable validation framework for future healthcare datasets
