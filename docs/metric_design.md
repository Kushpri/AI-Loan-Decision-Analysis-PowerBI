# Metric Design & Analytical Logic

This document explains the reasoning behind key metrics used in the
AI Loan Decision Audit & Operations Intelligence Platform.

---

## Approval Rate (%)
**Definition:**  
Percentage of loan applications approved by the AI system.

**Formula:**  
Approved Applications / Total Applications

**Why it matters:**  
Indicates how conservative or aggressive the AI decision engine is.
Lower approval rates suggest stricter risk thresholds.

---

## AI Confidence Score
**Definition:**  
A score representing the AI model’s confidence in its decision.

**Usage:**  
- Low confidence + Approval → potential risk escalation
- High confidence + Rejection → strong risk signal

**Operational Value:**  
Used to identify decisions that may require human review.

---

## Risk Level
**Definition:**  
Overall risk categorization of loan applications (Low / Medium).

**Why it matters:**  
Helps assess whether approvals are concentrated in safer segments
and whether higher-risk segments are being appropriately filtered.

---

## Income Group Fairness Analysis
**Objective:**  
Evaluate whether approval rates vary significantly across income groups.

**Insight Goal:**  
Detect potential socioeconomic bias in AI-driven decisions.

---

## Location-Based Analysis
**Objective:**  
Compare approval likelihood across Rural, Semi-Urban, and Urban areas.

**Why it matters:**  
Ensures geographic fairness and highlights infrastructure-driven bias.

---

## Human-in-the-Loop Concept
This dashboard is designed to act as a **monitoring and audit layer**.
While decisions are AI-generated, the insights enable:
- Manual review triggers
- Policy oversight
- Model governance discussions
