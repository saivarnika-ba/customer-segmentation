# Customer Revenue & Segmentation Dashboard
**Live Dashboard → [View Here](https://saivarnika-ba.github.io/customer-segmentation)**

> Built with Power BI · DAX · SQL · Python · Star Schema Data Modelling

---

## Business Problem
Revenue leadership had no segment-level visibility into customer lifetime value, churn risk, or year-on-year growth across 6,000+ customer records. Reporting was static, Excel-dependent, and delivered no actionable segmentation insight.

## What I Built
A full end-to-end BI solution:
- **Extracted & transformed** 6,000+ customer records using SQL (CTEs, window functions, joins)
- **Built a star-schema data model** in Power BI with fact and dimension tables
- **Developed DAX measures** for YoY revenue growth, customer lifetime value (CLV), and retention rate
- **Implemented Row-Level Security (RLS)** — region managers see only their own data
- **Delivered a 5-page interactive report** with drill-through, slicers, and bookmarks

## Key Findings
| Insight | Impact |
|---|---|
| Top 20% of customers generate ~65% of revenue | Pareto-validated via DAX RANKX |
| Churn risk peaks at Month 3 of customer lifecycle | Enables targeted Month 2 retention campaigns |
| DAX query optimisation | Reduced report load time by ~30% |

## Technical Stack
| Layer | Tool |
|---|---|
| Data Extraction | SQL — Joins, CTEs, Window Functions |
| Data Modelling | Star Schema (Fact + 4 Dimension tables) |
| Measures & KPIs | Power BI DAX — CALCULATE, RANKX, PERCENTILEX, time intelligence |
| Security | Row-Level Security (RLS) by region |
| Visualisation | Power BI — 5-page interactive report |
| Supporting Analysis | Python (Pandas) — data cleaning & profiling |

## Files in This Repo
```
index.html          → Live interactive dashboard (open in browser)
README.md           → This file
```

## Skills Demonstrated
`Power BI` `DAX` `SQL` `Star Schema` `Data Modelling` `RLS` `Python` `ETL` `KPI Design` `Stakeholder Reporting`

---
*Part of my analytics portfolio → [saivarnika-portfolio.netlify.app](https://saivarnika-portfolio.netlify.app)*# customer-segmentation
