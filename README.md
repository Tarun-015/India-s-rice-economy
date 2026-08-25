# From Paddy Field to P&L: India's Rice Economy for Strategic Agribusiness Decisions

## Overview

This project analyzes the historical trajectory of India's rice economy to identify trends, growth drivers, supply-side risks, and strategic opportunities for a rice procurement, processing, and trading business.

The analysis uses four official rice datasets provided in the case study:

- Minimum Support Price (MSP)
- Area Under Cultivation
- Yield Per Hectare
- Agricultural Production

The objective is to convert historical agricultural statistics into decision-ready insights for procurement, capacity planning, pricing, and working-capital decisions.

---

## Business Problem

Leadership of a mid-sized rice value-chain business needs to prepare its strategic and procurement plan for the coming season.

The key question is:

> **What does the historical trajectory of India's rice economy tell us about the risks and opportunities the business should plan for, and where should management focus first?**

The project examines whether changes in rice production are primarily driven by expansion in cultivated area or improvements in yield, how MSP has evolved relative to productivity and production, and where significant supply-side risks have occurred.

---

## Dataset

The analysis is based exclusively on the provided `Dattansh.xlsx` workbook.

| Dataset | Period | Unit |
|---|---|---|
| Minimum Support Price | 1975-76 to 2026-27 | ₹ per quintal |
| Area Under Cultivation | 1950-51 to 2025-26 | Lakh hectares |
| Yield Per Hectare | 1950-51 to 2025-26 | Kg per hectare |
| Agricultural Production | 1950-51 to 2025-26 | Lakh tonnes |

All datasets are restricted to rice at the all-India level and are linked using crop year.

---

## Analytical Approach

### 1. Trend Analysis

Long-term and decade-wise trends are analyzed for:

- MSP
- Cultivated area
- Yield
- Production

Major inflection points and structural changes are identified.

### 2. Growth Decomposition

Production growth is decomposed into:

- Area expansion
- Yield improvement

CAGR is calculated across relevant periods to understand the changing drivers of rice production.

MSP growth is also compared against productivity and production growth.

### 3. Correlation Analysis

Key relationships examined include:

- MSP vs Production
- Area vs Yield

Correlation is used to identify historical relationships, not to establish causality.

### 4. Volatility and Risk Analysis

Years with significant increases or declines in:

- Production
- Area
- Yield
- MSP

are identified to understand potential supply and procurement risks.

### 5. Forecasting

Historical patterns are used to develop near-term forecasts for selected variables.

Forecast assumptions and uncertainty are explicitly considered before translating forecasts into business recommendations.

---

## Business Lens

The analysis translates statistical findings into decisions related to:

- Procurement planning
- Milling and storage capacity
- Pricing strategy
- Supply risk management
- Working capital requirements

The objective is not only to explain what happened historically, but also to identify what management should consider when planning for future seasons.

---

## Key Deliverables

### Excel Analysis Workbook

Contains auditable calculations for:

- Trend analysis
- CAGR
- Growth decomposition
- Correlation
- Volatility
- Forecasting

### Power BI Dashboard

Interactive dashboard covering:

- MSP trends
- Area trends
- Yield trends
- Production trends
- Growth drivers
- Historical volatility
- Forecast outlook
- Business insights

### Insight Report

A concise executive presentation translating the analysis into prioritized strategic recommendations.

---

## Tools Used

- Microsoft Excel
- Microsoft Power BI
- Data Analysis
- Statistical Analysis
- Forecasting
- Business Intelligence

---

## Project Structure

```text
india-rice-economy-strategic-analytics/
│
├── README.md
│
├── data/
│   └── Dattansh.xlsx
│
├── excel/
│   └── Rice_Economy_Analysis.xlsx
│
├── powerbi/
│   └── Rice_Economy_Dashboard.pbix
│
├── presentation/
│   └── Rice_Economy_Insights.pptx
│
└── screenshots/
    └── dashboard-preview.png
