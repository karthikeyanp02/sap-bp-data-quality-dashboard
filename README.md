# sap-bp-data-quality-dashboard

SAP Business Partner Data Quality Dashboard

A Python-based data quality monitoring solution inspired by SAP Public Cloud Business Partner master data challenges.

## Problem Statement

In many SAP implementations, incomplete Business Partner records often go unnoticed until they cause downstream issues such as:
- billing failures
- missing tax information
- output issues
- audit inconsistencies

This project aims to proactively identify and prioritize poor-quality master data records before they impact business processes.

---

## Features

- Validates Business Partner master data
- Detects missing critical fields
- Assigns weighted quality scores
- Classifies records by severity
- Generates Excel dashboard reports
- Creates prioritized cleanup lists
- Root cause analysis for missing fields

---

## Tech Stack

- Python
- Pandas
- OpenPyXL
- XlsxWriter
- Faker

---

## Dashboard Preview

### Final Dashboard
<img width="1882" height="693" alt="Screenshot 2026-05-12 194710" src="https://github.com/user-attachments/assets/aec958e7-24c6-442b-8ac5-16af183998fe" />


### Cleanup List
<img width="1885" height="693" alt="image" src="https://github.com/user-attachments/assets/e380cb6b-30c5-46c0-a25e-3a503d502355" />


### Root Cause Analysis

<img width="1918" height="718" alt="image" src="https://github.com/user-attachments/assets/b8568c25-373b-462f-9b7c-bb614c0e7461" />


---

## Future Improvements

- GST validation logic
- Anomaly detection
- Streamlit web dashboard
- SAP CDS integration
- Automated data quality alerts

---

