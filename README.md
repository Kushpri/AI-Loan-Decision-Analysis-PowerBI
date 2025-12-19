AI Loan Decision Audit & Operations Intelligence Platform (Power BI)
📌 Project Overview

This project delivers an end-to-end analytical audit layer for AI-driven loan approval decisions using Power BI.

The platform is designed to monitor, interpret, and govern AI decision outcomes, focusing on:

Approval behavior

Risk distribution

Model confidence

Fairness across income and location segments

The objective is not just visualization, but decision intelligence — enabling stakeholders to understand how and where AI decisions may require oversight or intervention.

🎯 Business Problem Addressed

AI systems increasingly automate loan approvals, but organizations often lack:

Visibility into approval vs rejection patterns

Confidence-risk alignment checks

Fairness analysis across demographics

Human-in-the-loop audit readiness

This project acts as a decision audit & monitoring layer, supporting:

Risk governance

Model accountability

Policy-driven reviews

📊 Dashboards Overview
1️⃣ Executive Summary

High-level KPIs designed for leadership and risk stakeholders:

Total Loan Applications

Overall Approval Rate (%)

Average AI Confidence Score

AI Approval vs Rejection split

Application Volume by Risk Level

Executive insights highlighting decision trends

2️⃣ Decision Analysis

Deeper analytical views to assess fairness, risk, and confidence alignment:

AI Approval vs Rejection by Income Group (100% stacked)

Distribution of AI Confidence Scores

Approval distribution by Location Type (Urban / Semi-Urban / Rural)

Risk-based application volume

Interactive slicers for location-based drill-downs

Analytical summary explaining observed patterns

📈 Key Analytical Insights

Majority of applications fall under Low Risk, driving most approvals

Overall approval rate (~34.5%) reflects conservative AI decisioning

Rejections outweigh approvals, indicating strict risk thresholds

Approval rates improve with higher income groups

Urban and Semi-Urban locations show higher approval likelihood than Rural

AI confidence scores cluster at lower values, signaling cautious predictions

Confidence-risk alignment highlights areas suitable for human review

🧠 Metric Design & Governance Logic

Key metric definitions and analytical reasoning are documented separately to ensure transparency and reproducibility:

📐 Metric Design Documentation
👉 docs/metric_design.md

This includes:

Approval Rate calculation logic

AI Confidence Score interpretation

Risk categorization intent

Fairness analysis rationale

Human-in-the-loop monitoring concepts

🛠 Tools & Technologies

Power BI Desktop

Data Modeling & DAX Measures

KPI Cards & Interactive Visuals

100% Stacked Bar Charts, Column Charts, Donut Charts

Slicers & Filters for drill-down analysis

Analytical storytelling & governance-focused design

📂 Repository Contents
AI_Loan_Decision_Analysis.pbix   → Interactive Power BI dashboard
AI_Loan_Decision_Analysis.pdf   → Exported dashboard report
screenshots/                    → Dashboard preview images
docs/metric_design.md           → Metric definitions & analytical logic
README.md                       → Project documentation

🚀 How to Use

Download the .pbix file

Open using Power BI Desktop

Explore dashboards using slicers and filters

Review metric definitions in docs/metric_design.md

👤 Author

Priti Kushwaha
Aspiring Data Analyst | Analytics Engineer | AI Operations Analyst
