# 🧪 A/B Test: Landing Page Optimization

Analyzing an e-commerce A/B experiment (40K users, Jan 2026) to determine which landing page version maximizes conversion rate and revenue per user.

---

## Overview

An e-commerce marketing team ran a controlled experiment comparing two landing page versions (A vs. B). This project applies statistical hypothesis testing to answer five business questions and deliver a clear deployment recommendation.

---

## Key Results

| Metric | Page A | Page B |
|:-------|:------:|:------:|
| Conversion rate | 12.6% | **16.0%** |
| Avg. spend (converted) | Lower | **Higher** |
| Statistical significance | — | p < 10⁻²⁰ |

**Verdict:** Page B wins on both conversion and revenue metrics with overwhelming statistical confidence.

---

## Methods

- **Independent samples t-test** — average spend comparison (converted users only)
- **Two-proportion z-test** — conversion rate comparison
- **Chi-square test of independence** — segmentation by traffic source and user type

---

## Tech Stack

`Python` · `pandas` · `NumPy` · `SciPy` · `statsmodels` · `Matplotlib` · `Seaborn` · `Jupyter Notebook`

---

## Repository Structure

```
├── S9_Version_Student_Proyecto_Landing_Experiment.ipynb   # Full analysis
├── landing_experiment.csv                                  # Source dataset
└── README.md
```

---

## How to Run

```bash
git clone https://github.com/Danielvillamilc/ab-test-landing-page.git
pip install pandas numpy scipy statsmodels matplotlib seaborn
jupyter notebook S9_Version_Student_Proyecto_Landing_Experiment.ipynb
```

---

## Author

**Daniel Villamil** — Data Analytics · Bogotá, Colombia · [GitHub](https://github.com/Danielvillamilc)
