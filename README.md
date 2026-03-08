# Investigate a Dataset — TMDB Movie Analysis

**Udacity Data Analysis Project | Python · Pandas · Matplotlib · NumPy**

---

## Project Overview

Exploratory data analysis on the TMDB Movies dataset (10,866 movies, 21 columns) to investigate what factors are associated with a movie's adjusted revenue.

**Main Question:** Once we account for budget, are popularity and ratings still associated with adjusted revenue?

---

## Analysis Sections

- **Data Wrangling** — cleaning, handling missing values, replacing zeros with NaN
- **Exploratory Data Analysis** — distributions, correlations, and visualizations
- **Conclusions** — key findings and limitations of the analysis

---

## Key Findings

- Budget is the strongest predictor of adjusted revenue
- Popularity and vote average show positive associations with revenue even after accounting for budget
- A small number of high-budget outliers (e.g. blockbusters) heavily influence the results

---

## Files

| File | Description |
|------|-------------|
| `Investigate_a_Dataset.ipynb` | Full analysis notebook |
| `data/tmdb-movies.csv` | TMDB movie dataset |

---

## Tools & Technologies

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white)

---

## How to Run

```bash
pip install pandas numpy matplotlib jupyter
jupyter notebook Investigate_a_Dataset.ipynb
```

---

*Project completed as part of the Udacity Data Analysis and Descriptive Statistics Nanodegree*
