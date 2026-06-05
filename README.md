# Account Receivables & Debtor Aging Analysis

## Project Overview
This project provides an automated financial monitoring system for managing debtor aging. By transforming raw SAP data into interactive visualizations, the dashboard enables finance teams to identify overdue exposures, mitigate credit risk, and optimize working capital.

## The Business Problem
Managing outstanding invoices manually across multiple customer accounts often leads to delayed collections and limited visibility into high-risk exposures. The objective was to create a centralized "source of truth" that allows stakeholders to monitor Days Sales Outstanding (DSO) and aging buckets in real-time, replacing static, error-prone manual spreadsheets.

## Tech Stack & Methodology
* **Data Processing**: Extracted raw data from SAP and performed complex reconciliation using Advanced Excel. This involved data cleaning, removing duplicates, and standardizing account names to ensure 100% data integrity before modeling.
* **Dashboarding**: Power BI Desktop.
* **Analytical Logic**: Developed custom DAX measures to categorize debt into 30, 60, and 90+ day aging buckets. This allowed for risk-weighted analysis, giving higher visibility to debts that are significantly past due.
* **Data Refresh**: Designed the data model to allow for easy updates, ensuring that as new SAP exports are added, the dashboard reflects the current status with minimal manual intervention.

## Key Insights & Results
* **Risk Mitigation**: Successfully flagged high-risk accounts that were consistently driving the majority of overdue balances.
* **Reporting Efficiency**: Reduced monthly manual data consolidation time, allowing the finance team to shift their focus from manual entry to proactive collection strategy.
* **Strategic Visibility**: Provided leadership with a real-time dashboard to monitor monthly cash collection performance against organizational targets, enabling faster credit review meetings.

## Business Recommendations
* **Proactive Collection**: Implement a tiered follow-up strategy, focusing debt-recovery efforts on the 60+ day aging segment identified as "high-impact" in the dashboard.
* **Policy Refinement**: Use the historical trends revealed by the dashboard to reassess credit limits for customers who consistently fail to meet payment terms, thereby reducing future bad debt exposure.

---

## Project Resources
* **View Dashboard PDF**: [AR DASHBOARD..pdf](AR%20DASHBOARD..pdf)
* **Download PBIX File**: [AR DASHBOARD.pbix](AR%20DASHBOARD.pbix)
