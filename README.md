# HR Analytics Dashboard: Employee Attrition and Workforce Analysis

## Overview
An interactive Power BI report that analyzes employee attrition, retention,
promotion and retrenchment, and identifies which employee groups are most at
risk of leaving. The goal is to help HR prioritize retention actions.

## Business Problem
HR needed to understand why employees leave and which groups are most at risk.
This dashboard answers:
- What is the overall attrition rate and how is it changing?
- Which roles, age groups and salary bands see the highest attrition?
- Does overtime affect attrition?
- Which employees should HR focus on first?

## Tools & Technologies
- Power BI (interactive dashboard)
- DAX (measures and rule-based risk score)
- Power Query (data cleaning and merging)
- Microsoft Excel (source data)

## Dataset
- 1,470 employee records
- Multiple Excel source files merged into one employee-level master table
- Source: [Kaggle IBM HR Analytics dataset / other, please confirm]

## Data Preparation
- Cleaned and standardized data in Power Query
- Merged multiple Excel sources into a single employee-level master table
- Reconciled KPIs against the source data to make sure the numbers match

## Key Metrics (KPIs)
- Attrition rate: 16%
- Retention rate
- Promotion and retrenchment counts
- Employee risk level (High / Medium / Low)

## Key Insights
- Overtime employees leave at about 3x the rate of others (30.5% vs 10.4%).
- Attrition is highest among Sales Representatives (40%), employees under 25
  (39%) and employees earning under 3K (29%).
- 54 employees were marked for both promotion and retrenchment, which is a
  data conflict HR should review.
- Employees in the High-risk segment show 32% attrition vs 8% in the
  Low-risk segment, so the risk score separates groups well.

## Recommendations
- Review overtime policies and workload, especially in Sales roles.
- Build early-career engagement and mentoring for employees under 25.
- Review pay for lower salary bands.
- Resolve the promotion and retrenchment conflicts.
- Use the risk score to prioritize retention conversations.
