# 👥 HR Employee Attrition Analysis

> EDA on 1,470 IBM HR records to identify the key drivers behind employee attrition.

---

## Overview

Analyzed IBM's HR dataset to uncover why employees leave. The project covers data cleaning, exploratory analysis across multiple dimensions, and actionable business recommendations for HR teams.

---

## Key Findings

| # | Finding | Rate |
|---|---------|------|
| 1 | Employees with 0–2 years tenure leave at **~47%** — highest risk window | 47% |
| 2 | Employees doing OverTime leave at **~31%** vs ~10% for those who don't | 31% vs 10% |
| 3 | Sales department has the highest attrition across all departments | ~21% |

---

## Analysis Structure

| Step | Focus |
|------|-------|
| 1 — Data Cleaning | Drop zero-variance columns, create tenure bands, verify missing values |
| 2 — Department Analysis | Attrition rates across HR, Sales, and R&D |
| 3 — Tenure Analysis | Risk by years at company (0–2, 3–5, 6–10, 10+) |
| 4 — OverTime & Income | Impact of overtime and monthly income on attrition |

---

## Business Recommendations

- Focus onboarding and engagement programs on employees in their **first 2 years**
- Review OverTime policies — employees working extra hours are **3x more likely** to leave
- Investigate compensation and career growth paths in the **Sales department**

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## Dataset

| Field | Info |
|-------|------|
| Source | IBM HR Analytics (Kaggle) |
| Size | 1,470 employees · 35 features |
| Target | Attrition (Yes / No) — 16.1% attrition rate |

---

## Author

**Nooreldin Mahmoud** · [nooreldean.mahmoud@gmail.com](mailto:nooreldean.mahmoud@gmail.com)
