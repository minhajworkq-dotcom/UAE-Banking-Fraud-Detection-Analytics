# UAE Banking Fraud Detection Analytics

![Python](https://img.shields.io/badge/Python-3.13-blue)
![MySQL](https://img.shields.io/badge/MySQL-8.0-orange)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![Data](https://img.shields.io/badge/Data-Synthetic-lightgrey)

## Overview

A banking transaction risk analytics project built using **Python, MySQL, SQL and Power BI**.

The project demonstrates how transaction level behavioral signals can be engineered using SQL, converted into investigation risk scores, and presented through an interactive Power BI dashboard.

The dataset is entirely synthetic and designed for portfolio and educational purposes.

> **Important:** The project identifies transactions requiring further investigation based on predefined behavioral rules. The alerts are **not confirmed fraud cases** and the results do not represent real UAE banking statistics.

---

## Dashboard Preview

### Executive Risk Dashboard

![Executive Risk Dashboard](screenshots/01-executive-risk-dashboard.png)

### Fraud Detection & Risk Analysis

![Fraud Detection & Risk Analysis](screenshots/02-fraud-detection-risk-analysis.png)

### UAE Geographic Risk

![UAE Geographic Risk](screenshots/03-uae-geographic-risk.png)

### Customer & Account Risk

![Customer & Account Risk](screenshots/04-customer-account-risk.png)

### Transaction Investigation

![Transaction Investigation](screenshots/05-transaction-investigation.png)

---

# Project Architecture

```text
Python Synthetic Data
        ↓
CSV Dataset
        ↓
MySQL Database
        ↓
SQL Investigation Rules
        ↓
Risk Scoring
        ↓
fraud_alerts
        ↓
Analytical SQL Views
        ↓
Power BI Dashboard
