# Commonwealth Bank Fraud Detection Dashboard (Splunk SIEM)

## Overview

This project was completed as part of the Commonwealth Bank Introduction to Cybersecurity Job Simulation on Forage.

The objective was to analyse transaction data using Splunk Enterprise to identify fraud trends, suspicious merchant behaviour, and transaction category risks.

---

## Task Objective

Analyse cyber and transaction data to uncover fraud patterns and visualise insights using Splunk dashboards.

---

## Dataset

The dataset contains simulated banking transactions including:

- Transaction category
- Customer identifiers
- Merchant IDs
- Gender information
- Fraud indicators
- Transaction amounts
- Postcode origin

Data was ingested into Splunk Enterprise for indexing and analysis.

---

## Tools Used

- Splunk Enterprise 10.x
- SPL (Search Processing Language)
- Dashboard Studio

---

## Analysis Performed

### Fraud Category Distribution

-sourcetype="fraud_detection.csv"
| top category


Identified the most common fraud categories.

---

### KPI Metrics

- Total Fraud Transactions
- Gender Fraud Cases

---

### Fraud Trend Analysis

Transaction behaviour analysed across merchants and categories.

---

### Merchant Risk Score

Visualised fraud exposure using gauge metrics.

---

## Dashboard Features

- Interactive bar charts
- Pie chart distribution
- KPI indicators
- Trend analysis visualisation
- Merchant risk scoring

---

## Dashboard Preview

![Dashboard Overview](screenshots/dashboard_overview.png)

---

## Key Findings

- Transportation category showed the highest fraud frequency.
- Fraud cases varied across customer groups.
- Certain merchants showed elevated risk exposure.

---

## Skills Demonstrated

- SIEM Analysis
- Log ingestion
- SPL Querying
- Threat investigation
- Data visualisation

---

## Certification

Completed under:

Commonwealth Bank Introduction to Cybersecurity Virtual Experience — Forage.
