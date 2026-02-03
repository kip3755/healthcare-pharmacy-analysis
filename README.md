Pharmacy Operations Performance Analysis (2025)

 Project Overview
An in-depth analysis of pharmacy supply chain and service performance across two centers using operational data from January–November 2025. This project evaluates drug requisition efficiency, supplier performance, order fulfillment, and patient satisfaction, identifying bottlenecks that affect service delivery.

Business Objectives:
- Measure Drug Requisition Turnaround Time (TAT)
- Evaluate supplier delivery performance
- Track order fulfillment and prescription fill rates
- Identify drugs and vendors causing delays
- Assess overall patient satisfaction

Dataset
The dataset contains anonymized pharmacy operational data from Active level 5 hospital, including:

- Columns: `InvestigationName`, `Results_Received_TAT_Min`, `Purchase_Order_TAT`, `GRN_Approval_TAT`, `Prescription_Fill_Rate`, `Overall_Satisfaction_Score`, `SupplierName`
- Period: January – November 2025
- Rows: Several thousand transactions across two pharmacy centers
- Privacy: All personal identifiers removed; patient-level data anonymized

Analysis & Findings

Centre 1 Pharmacy (Feb – Nov 2025)
Key Metrics:
- Number of Suppliers: 33
- Median Drug Requisition TAT: 3 days
- Average Drug Requisition TAT: 5 days
- Purchase Order Approval TAT: 7 hours
- GRN Approval TAT: 15 minutes
- Order Fulfillment Rate: 88%
- Prescription Fill Rate: 93.71%
- Overall Satisfaction Score: 97%

Findings:
- Internal processing is highly efficient; PO & GRN approvals are rapid.
- Gap between median (3 days) and average TAT (5 days) indicates occasional outlier delays.
- Monthly requisition TAT stable at ~6 days — predictable procurement performance.
- A few suppliers contribute to extreme delays (>55 days).
- Critical drugs (e.g., Sitagliptin, Artesunate) sometimes experience 40–60 day delays.

Risk Areas:
- Dependence on underperforming vendors
- Long delays for essential medications


Centre 2 Pharmacy (Jan – Nov 2025)
Key Metrics:
- Number of Suppliers: 51
- Median Drug Requisition TAT: 6 days
- Average Drug Requisition TAT: 10 days
- Order Fulfillment Rate: 90%
- Prescription Fill Rate: 90%
- Overall Satisfaction Score: 86%

Findings:
- Larger supplier base increases operational complexity.
- Median vs average TAT discrepancy shows significant vendor delays.
- Some drugs face extreme requisition TATs of 40–94 days.
- Monthly TAT fluctuates between 5–8 days — inconsistent supplier reliability.
- Lower fill rates correlate with reduced patient satisfaction.

Comparative Insights (Centre 1 vs Centre 2)

| Metric | Centre 1 | Centre 2 |
|--------|----------|----------|
| Median Requisition TAT | 3 days | 6 days |
| Avg Requisition TAT | 5 days | 10 days |
| Order Fulfillment Rate | 88% | 90% |
| Prescription Fill Rate | 93.71% | 90% |
| Satisfaction Score | 97% | 86% |

Interpretation:
- Centre 1 outperforms Centre 2 in speed, consistency, and satisfaction.
- Supplier performance, not internal processing, drives delays.
- Larger supplier networks increase risk unless tightly managed.

Dashboard & Visualizations
Below are key visualizations from the analysis:

## Centre 2 Dashboard Preview

![Centre 1 Dashboard Preview](data/dashboard/data/dashboard/dashboard_preview.png%20Centre%201.png)

*Dashboard preview showing key pharmacy KPIs for Centre 1.*

## Centre 2 Dashboard Preview

![Centre 2 Dashboard Preview](https://github.com/kip3755/healthcare-pharmacy-analysis/blob/main/data/dashboard/images/Centre%202%20%20dashboard_preview.png%20(1).png?raw=true)


*Dashboard preview showing key pharmacy KPIs for Centre 2.*

 Key Insights
- Supplier performance is the primary driver of delays, not internal workflows.
- Certain critical drugs face high TAT risks, potentially impacting patient care.
- Larger supplier networks require tighter monitoring and consolidation.
- Median vs average analysis highlights outlier delays, enabling targeted interventions.

 Business Recommendations
- Supplier Performance Management: Implement SLAs with penalties for late deliveries.
- Critical Drug Monitoring: Flag high-risk drugs for proactive procurement.
- Vendor Consolidation: Reduce supplier count to high-performing vendors.
- Early Warning Dashboards: Automate alerts for drugs exceeding TAT thresholds.
- Cross-Centre Best Practices: Apply Centre 1 practices to Centre 2 for consistency.

Skills & Tools Used
- Tools: Power BI, DAX, Excel, GitHub
- Skills: Data cleaning, KPI analysis, median vs average computation, visualization, portfolio documentation

 Disclaimer
All data used is anonymized. No patient-identifiable information is included.
