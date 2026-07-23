# Exported Dataset

## Overview
This folder contains datasets exported from Power BI dashboards.

These datasets are used as the input source for the n8n AI workflow to automate business analysis and generate AI-powered recommendations.

## Contents

The exported files may include:

 - Executive_KPIs.csv
 - Monthly_Revenue.csv
 - Sales_Performance.csv
 - Customer_Segmentation.csv
 - Customer_Details.csv
 - Delivery_Performance.csv
 - Product_Performance.csv
 - Campaign_Performance.csv

Power BI
      │
      ▼
Export CSV
      │
      ▼
GitHub Repository
      │
      ▼
n8n Workflow
      │
      ▼
Read CSV Files from GitHub
      │
      ▼
Merge Data
      │
      ▼
AI Agent (OpenAI / Gemini)
      │
      ▼
Evaluate Campaign Performance
      │
      ├── KPI Analysis
      ├── Customer Segment Advisor
      ├── Churn Alert
      ├── Repeat Purchase Analysis
      ├── Product Recommendation
      ├── Campaign Recommendation
      ├── Content Generator
      └── Executive Report
      │
      ▼
Save Report (GitHub / Google Drive / Email / Notion)

## Purpose

The exported datasets enable the AI Agent to:

- Analyze business KPIs
- Evaluate marketing campaign performance
- Identify sales trends
- Segment customers
- Generate actionable business insights
- Recommend optimization strategies
