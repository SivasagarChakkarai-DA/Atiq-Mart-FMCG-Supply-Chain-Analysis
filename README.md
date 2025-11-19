# Atiq-Mart-FMCG-Supply-Chain-Analysis
Excel: Data Preparation  Tableau: Data Visualization and Dashboard Building 

Supply Chain Performance | LIFR | VOFR | OTIF | OT | IF | COCT | DOD

AtliQ Mart is a leading FMCG retail chain operating across Gujarat with major distribution hubs in Ahmedabad, Surat, and Vadodara.
The company wants to measure, track, and optimize supply chain performance by analyzing:

Delivery punctuality

Delivery completeness

Fulfilment accuracy

Order processing cycle time

City-wise & customer-wise performance

Category-wise delivery behavior

This project leverages Excel for data cleaning & modeling and Tableau for interactive dashboards to help AtliQ leadership take fast, data-driven decisions.

⭐ 1. Project Overview

This project analyzes the Order Line–Level and Order–Level performance across AtliQ’s FMCG operations.

Using Excel for preprocessing and Tableau for visualization, the project delivers:

Combined KPIs (OT, IF, OTIF, LIFR, VOFR, COCT, DOD)

City-level and Category-level delivery trends

Product-wise fulfilment breakdown

Customer-level order behavior

Historical monthly trends

Detailed performance overview at every layer

This analysis enables supply chain managers to identify bottlenecks in delivery operations and drive continuous improvement.

⭐ 2. Business Problem

AtliQ Mart’s supply chain team needs to answer:

✔ Are deliveries reaching stores on time?
✔ Are shipments complete, without shortages?
✔ Which cities, categories, or customers are underperforming?
✔ Which KPIs consistently fail to meet the target?
✔ Is there a seasonal trend or monthly variation?
✔ What should be the focus areas for the next improvement cycle?

The Tableau dashboard helps answer these questions interactively.

⭐ 3. Tools & Technologies
Excel:

Data cleaning

Duplicate handling

KPI formula logic

Monthly aggregations

Pivot-driven summaries

Pre-modeling transformations

Tableau:

Relationship modeling

KPI cards

Line charts, bar charts, heatmaps

Filters (Month, Week, City, Category)

City-wise, Product-wise, Customer-wise breakdown

Interactive drilldowns

Your supplied model screenshot matches this structure.
It creates flexible grain for Line-Level and Order-Level visual analysis.

⭐ 5. KPI Definitions (Used in Dashboard)
KPI	Meaning	Purpose
OT %	On-Time Delivery	Measures punctuality vs target
IF %	In-Full Delivery	Measures completeness (no shortages)
OTIF %	On-Time In Full	Combined delivery accuracy & reliability
LIFR %	Line Fill Rate	Product-level fulfilment
VOFR %	Volume Fill Rate	Shipment-level fulfilment by volume
COCT (Days)	Customer Order Cycle Time	Avg time taken to complete an order
DOD (Days)	Delay on Delivery	Measures delivery deviation

Targets are built into dim_targets_orders tables.

⭐ 6. Tableau Dashboard Story

The Tableau story consists of 4 pages:

📌 Page 1 — Welcome Page (Executive Summary)

🎯 Introduces the dashboard purpose:

Improve fulfilment efficiency

Identify strengths & gaps

Monitor operational performance

Benchmark against defined targets

🎯 KPIs explained: OT, IF, LIFR, VOFR, OTIF, COCT, DOD

📌 Page 2 — Overview Dashboard

This page provides a global snapshot of:

✔ KPI Cards

OT Target 86.09%

OT % 59.03%

IF % 52.78%

OTIF % 29.02%

LIFR % 65.96%

VOFR % 96.59%

✔ Visuals

Delivery by Product

Delivery by Customer

LIFR & VFR trends by product

Time-over-time KPI lines (March–August)

🎯 Insight Highlights:

OT % and IF % are consistently below target

VOFR remains excellent (~97%)

Some customers & products are repeatedly underperforming in OT/IF

📌 Page 3 — Line-Level Dashboard

Focuses on product-level deliveries:

Visuals include:

LIFR vs VOFR by City & Category

OT vs Target (trend)

IF vs Target (trend)

OTIF vs Target

Ordered vs Delivered QNTY

Orders by Customer

🎯 Insights:

Surat & Ahmedabad have slightly higher delivery accuracy than Vadodara

Food category shows best fulfilment

Multiple customers consistently order high volumes but receive delayed shipments

📌 Page 4 — Order-Level Dashboard

Focuses on customer-level & city-level performance:

Visuals include:

OT by City vs Target

IF by City vs Target

OTIF by City vs Target

Orders by City

Orders over Time

Customer-level Order Distribution

🎯 Insights:

Surat = best OT performance (~61%)

Vadodara shows lowest OT & IF

Order volumes peak during March–May

Large clients like Lotus Mart, Real Fresh, and Propal Mart drive most orders

⭐ 7. Key Insights (Business Findings)
🔹 1. OT performance heavily below target

Actual OT ~59% vs Target 86% ⇒ punctuality is the biggest improvement area.

🔹 2. IF performance also below expectations

Actual IF ~52% vs Target 76% ⇒ many orders are incomplete.

🔹 3. OTIF at only 29%

Combined accuracy is extremely low, signaling systemic issues.

🔹 4. VOFR is excellent (96.59%)

Volume-based fulfilment is stronger than line-level fulfilment.

🔹 5. Certain cities consistently underperform

Vadodara shows low OT & IF, requiring targeted investigation.

🔹 6. Top customers show varying fulfilment challenges

Lotus Mart and Real Fresh show strong order frequency but inconsistent delivery accuracy.

🔹 7. Product-level fulfilment shows volatility

Many beverage and dairy SKUs fluctuate month-to-month.
