# Healthcare Operations Performance Analysis

An end-to-end operational analytics solution built on **SQL-based ETL pipelines and Power BI**, converting 50,000+ raw hospital records into governed, decision-ready KPI dashboards for executive management — covering patient operations, doctor performance, financial metrics, and staff utilization across departments.

> **Impact:** Cut recurring reporting turnaround by 60%, eliminated manual data review, and enabled data-driven capacity planning decisions through a single, trustworthy operational view.

<img width="1441" height="819" alt="Hospital Dashboard Overview" src="https://github.com/user-attachments/assets/f3b822cc-4736-4801-8110-aa2f2e13ea3c" />

---

## Why This Project

Hospitals generate large volumes of siloed data across patients, doctors, finance, and staff — but raw data alone doesn't drive decisions. This project builds a **full operational analytics pipeline**: from data extraction and reconciliation, through statistical analysis and anomaly detection, to executive-facing KPI dashboards — so management can move from *"what happened"* to *"what should we do next"* without manually digging through spreadsheets.

The focus throughout was **data quality and reconciliation first** — consolidating records from multiple departments, applying validation and consistency checks, and only then layering on visualization. This mirrors how production-grade BI is delivered in real enterprise settings, where governance and audit-readiness are non-negotiable.

---

## Problem Statement

Hospital management lacked a unified, reliable view of operations. Data was siloed across departments — patients, doctors, finance, and staff — with no standardized process to surface trends, flag anomalies, or support resource allocation decisions. The challenge: convert this fragmented raw data into a governed analytics system that highlights risks, identifies operational bottlenecks, and drives faster, data-backed decisions.

---

## Objectives

- Consolidate and clean **50,000+ patient, financial, and operational records** into analytics-ready datasets using SQL ETL pipelines
- Apply **CTEs, window functions, and reconciliation checks** to validate data quality before any analysis or visualization
- Surface **operational bottlenecks, resource utilization gaps, and performance anomalies** through statistical analysis and EDA
- Build **executive KPI dashboards** for department-wise and hospital-wide performance tracking
- Deliver **prioritized, data-driven recommendations** to support capacity planning and stakeholder decision-making
- Reduce manual reporting effort and enable faster, cross-functional decision-making through interactive, self-serve views

---

## Tools & Technologies

| Category | Tools |
|----------|-------|
| **Data Extraction & Transformation** | SQL (CTEs, Window Functions, Aggregations), Power Query |
| **Data Quality & Governance** | Reconciliation Checks, Validation Queries, Anomaly Flagging |
| **Analytics & Statistical Analysis** | EDA, Trend Analysis, Resource Utilization Analysis, KPI Development |
| **BI & Visualization** | Power BI (DAX, Power Query), Excel |
| **UI Planning** | Figma |

---

## Pipeline Architecture

The project follows a layered, production-style approach: **Extract → Validate → Transform → Model → Visualize → Recommend**

### 1. Data Extraction & ETL Pipeline
SQL-based pipelines consolidate raw records from patient, financial, and operational sources into a unified analytics layer. CTEs and window functions handle running totals, department-wise aggregations, and trend calculations. **Reconciliation checks are applied at each stage** to catch inconsistencies, missing values, and data gaps before they reach the dashboard layer — ensuring governance-ready, audit-reliable outputs.

### 2. Statistical Analysis & EDA
Before visualization, structured EDA was performed across all data domains to:
- Identify high-traffic departments driving hospital load
- Surface revenue vs. cost imbalances across departments
- Detect anomalies in admission patterns, doctor workload, and staff utilization
- Flag data quality gaps that impacted reporting accuracy

Findings were translated into **prioritized recommendations** for management — not just charts, but actionable next steps.

### 3. Executive KPI Dashboard — Overview
High-level hospital performance at a glance — admission/discharge trends, revenue summary, and operational KPIs for management review. Designed for non-technical stakeholders who need answers fast, not queries.

<img width="1441" height="819" alt="Overview Dashboard" src="https://github.com/user-attachments/assets/91245dfb-ff1d-4e71-bcb2-556110ca39d9" />

### 4. Patient Analysis
- Patient demographics and disease-wise distribution
- Admission and discharge trends over time
- Identification of demand patterns to inform capacity planning

### 5. Doctor Performance Analysis
- Doctor workload distribution across departments
- Department-wise availability and coverage gaps
- Performance metrics to support staffing decisions

### 6. Finance Dashboard
- Revenue vs. expenses tracking by department and time period
- Monthly and yearly financial trend analysis
- Identification of revenue-generating vs. cost-heavy areas

### 7. Staff Utilization Analysis
- Staff count and role distribution across departments
- Utilization insights to support allocation and hiring decisions

---

## Key Insights & Business Impact

| Finding | Business Action Enabled |
|---|---|
| Identified high-traffic departments driving disproportionate hospital load | Informed capacity planning and resource reallocation |
| Detected revenue-generating vs. cost-heavy departments | Enabled targeted financial optimization decisions |
| Surfaced anomalies in patient inflow patterns | Supported proactive staffing and scheduling |
| Flagged data quality gaps across source records | Resolved reconciliation issues improving KPI accuracy |
| Identified doctor workload imbalances | Highlighted staffing gaps for management review |

---

## Impact

- **60% reduction** in recurring reporting turnaround time
- **Eliminated manual data review** across recurring stakeholder reporting cycles
- Delivered a **single, trustworthy operational view** replacing fragmented, spreadsheet-based reporting
- Enabled **data-driven capacity planning decisions** for hospital management
- Surfaced hidden operational bottlenecks and resource gaps that were previously invisible in raw data

---

## What I'd Build Next

- **Automate the ETL layer** — schedule SQL extraction pipelines to refresh dashboards automatically, removing the last remaining manual step
- **Add anomaly detection** on key metrics (sudden revenue drops, abnormal admission spikes, doctor workload outliers) with automated alerts
- **Extend reconciliation checks** into a reusable validation framework applicable across future healthcare and operational datasets
- **Integrate forecasting** (Prophet / ARIMA) for patient demand prediction and revenue trend forecasting to shift from reactive to proactive decision-making
