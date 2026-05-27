# capstone-project
HIIM capstone - health data analytics and process improvement

# Medicare Hospital Data Analytics (2013–2022)

An end-to-end data analytics project exploring Medicare hospital discharge
and payment trends across the United States over a 10-year period.
Built as part of the B.S. in Health Information and Informatics Management
at Texas State University.

---

## Project Overview

This project analyzes Medicare hospital geography and service data from
2013–2022 to uncover trends in discharges, submitted charges, and Medicare
payments across states and Diagnosis-Related Groups (DRGs).

**Key questions explored:**
- Which DRGs account for the highest average yearly discharges?
- How have total Medicare discharges trended over time?
- How do submitted charges compare to actual Medicare payments?
- Which states carry the highest Medicare discharge volume?
- Which DRGs show the steepest charge growth over the decade?

---

## Dataset

- **Source:** Medicare Hospitals Geography Service Data (CMS)
- **Records:** 10 years of Medicare inpatient data (2013–2022)
- **Key fields:** DRG code/description, geographic level, state,
  total discharges, average submitted covered charge, average total
  payment, average Medicare payment

---

## Visualizations

| Chart | Description |
|-------|-------------|
| Top DRGs by Avg Discharges | Horizontal bar chart of the top 10 DRGs by average yearly discharges |
| Submitted Charges vs Payments | Scatter plot comparing submitted charges to total and Medicare payments |
| Discharges by State | Bar chart of average yearly discharges by state |
| Total Discharges Over Time | Line chart tracking national discharge trends 2013–2022 |
| Avg Medicare Payments Over Time | Line chart of average Medicare payment growth over the decade |
| Avg Charges by DRG Over Time | Multi-line chart tracking charge trends for the top 10 DRGs |

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

- **Python** — data loading, cleaning, and transformation
- **Pandas** — data wrangling and aggregation
- **Matplotlib** — chart generation
- **Panel** — interactive dashboard layout
- **Jupyter Notebook** — analysis environment

---

## How to Run

```bash
# Install dependencies
pip install pandas matplotlib panel jupyter

# Launch the notebook
Jupyter Notebook Capstone-1.ipynb
```

---

## Author

**Cynthia Ferley** — Data Analyst | Texas State University '26
[github.com/cferley](https://github.com/cferley)
