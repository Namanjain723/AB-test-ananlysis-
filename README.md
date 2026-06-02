<div align="center">

# 🧪 A/B Testing Analysis

### Did the change actually work? A statistical A/B test that separates real impact from noise.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

</div>

---

## 📌 Overview

This project runs a complete **A/B test** comparing a **control group** against an
**experimental group** to decide whether an intervention produced a *statistically
significant* improvement — not just a difference that could be down to chance.

## 🗂️ Data
`test_group.csv` — performance records for both groups, with a **`Score`** metric used as the success measure.

## 🔬 Approach
1. **Load & explore** the two groups; compare summary statistics and distributions.
2. **Visualise** the score distributions (Matplotlib / Seaborn) to sense-check the data.
3. **Hypothesis test** — an independent two-sample **t-test** (`scipy.stats.ttest_ind`) on the scores.
4. **Decide** — interpret the **t-statistic and p-value** against a 0.05 significance level and state whether the difference is real.

## 💡 Outcome
A clear, evidence-based verdict on whether the experimental variant outperforms the control — the same rigour used to validate product, marketing and pricing experiments.

## 🧰 Tech stack
**Python · Pandas · NumPy · SciPy · Matplotlib · Seaborn · Jupyter**

## ▶️ Run
```bash
git clone https://github.com/Namanjain723/AB-test-ananlysis-.git
pip install pandas numpy scipy matplotlib seaborn jupyter
jupyter notebook "AB TEST ANALYSIS (TASK-3).ipynb"
```

---

## 👤 Author
**Naman Jain** — Data Analyst & AI Developer
🌐 [Portfolio](https://pixlforgestudio03.netlify.app/) · ✉️ namancric18@gmail.com · 🐙 [@Namanjain723](https://github.com/Namanjain723)
