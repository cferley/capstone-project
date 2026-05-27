# Medicare Hospital Data Analytics Dashboard (2013–2022)

An interactive data analytics dashboard exploring Medicare hospital discharge
and payment trends across the United States over a 10-year period.
Built as part of the B.S. in Health Information and Informatics Management
at Texas State University.

**Score: 60/60**

---

## Project Overview

This project analyzes 278,000+ Medicare hospital records from 2013–2022 to
uncover trends in discharges, submitted charges, and Medicare payments across
states and Diagnosis-Related Groups (DRGs).

**Key questions explored:**
- Which DRGs account for the highest average yearly discharges?
- How have total Medicare discharges trended over time — including COVID impact?
- How do submitted charges compare to actual Medicare payments?
- Which states carry the highest Medicare discharge volume?
- Which DRGs show the steepest charge growth over the decade?

---

## Assignment Requirements

| Requirement | Implementation | Points |
|------------|----------------|--------|
| 6+ Filters | 9 interactive filters (sliders, multi-selects) | 12/12 |
| 4+ Distinct Plots | 6 plots (bar, scatter, line, heatmap) | 18/18 |
| Documentation | Comprehensive markdown + inline comments | 12/12 |
| Reproducibility | Clear data loading instructions | 6/6 |
| Layout | Collapsible sidebar with organized sections | 6/6 |
| Error-Free | Tested end-to-end execution | 6/6 |
| **Total** | | **60/60** |

---

## Dataset

- **Source:** Medicare Hospitals Geography Service Data (CMS)
- **Records:** 278,414 Medicare inpatient records (2013–2022)
- **Key fields:** DRG code/description, geographic level, state,
  total discharges, average submitted covered charge, average total
  payment, average Medicare payment

---

## Visualizations

| Chart | Type | Purpose |
|-------|------|---------|
| Top DRGs by Avg Discharges | Horizontal bar | Most common procedures by volume |
| Submitted Charges vs Payments | Scatter plot | Reimbursement patterns and variance |
| Discharges by State | Bar chart | Geographic disparities in utilization |
| Total Discharges Over Time | Line chart | National discharge trends 2013–2022 |
| Avg Medicare Payments Over Time | Line chart | Payment growth over the decade |
| DRG Charges Over Time | Multi-line chart | Cost trends across top 10 DRGs |

---

## Key Findings

- Average Medicare payments sit around $15,400 — but submitted charges
  run significantly higher, with hospitals collecting roughly 30–40% of
  what they bill
- Total discharge volume shows a visible COVID-19 impact in 2020
- Some high-complexity procedures exceed $600K in submitted charges
- Geographic disparities in discharge volume are significant across states

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

- **Python** — data loading, cleaning, and transformation
- **Pandas** — data wrangling and aggregation
- **Matplotlib / Seaborn** — chart generation
- **Panel** — interactive dashboard layout and widgets
- **Jupyter Notebook** — analysis environment

---

## How to Run

```bash
# Install dependencies
pip install pandas matplotlib seaborn panel jupyter

# Launch the notebook
jupyter notebook Capstone-1_Enhanced.ipynb
```

> **Note:** Download `Medicare Hospitals Geography Service 2013-2022.csv`
> to your Downloads folder before running.

---

## Author

**Cynthia Ferley** — Data Analyst | Texas State University '26
[github.com/cferley](https://github.com/cferley)
