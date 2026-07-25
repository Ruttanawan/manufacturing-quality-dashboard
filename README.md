# Manufacturing & Quality Performance Dashboard

## Overview

This project is an interactive Power BI dashboard designed to monitor manufacturing and quality performance. It provides key production KPIs, defect analysis, machine performance, and supplier quality metrics to support data-driven decision-making in a manufacturing environment.

![Dashboard Preview](Dashboard_preview.png)

---

## Summary
This dashboard provides high-level visibility for plant managers and quality engineers to track production yield, analyze defect root causes, and monitor supplier compliance.

---

## Dataset
- Simulated manufacturing dataset generated for portfolio purposes
- Business scenarios and KPI structure are based on real manufacturing quality processes

---

## Key Features & Metrics
* **KPI Header Cards:** Real-time tracking of `Overall Yield Rate (97.03%)`, `Defect Rate`, `Out of Control Rate`, and `Total Actual Quantity`.
* **Production & Yield Trend:** Combined Column and Line chart for monthly volume vs. yield rates.
* **Pareto Defect Analysis:** Identifies top cost-contributing defects (*Foreign Particle Inclusion & Surface Contamination*).
* **Machine & Supplier Quality:** Conditional formatting highlights high-risk areas:
  * Highest OOC Machine: *Injection Molding A2 (3.87%)*
  * Top Defect Supplier: *Global Synthetic Supplies (32 PPM, 31.48% Lot Failure)*

---

## Tools
* **Microsoft Power BI**
* **Data Transformation:** Power Query
* **Data Modeling:** DAX (Calculated Measures)

---

## Project Files
* `Manufacturing performance dashboard.pbix` - Power BI Desktop File
* `Dashboard_preview.png` - Dashboard Preview Image
