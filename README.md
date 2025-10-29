

# 📘 Soil Depth Effect Analysis

Python code for testing **statistical significance** of soil pH across **depth, treatment, and time**, including optional transformations to meet model assumptions. Supports parametric (Welch’s t-test) and non-parametric (Mann–Whitney U) analyses.

---

## 📁 Data

* **pH** – Response variable
* **Depth** – Soil depth (categorical)
* **Treatment** – Experimental groups
* **Day** – Time points

---

## 🔄 Transformations & Diagnostics

* Options: `log`, `sqrt`, `Box-Cox`
* Residual checks via `check_model()`: histogram, Q–Q plot, Shapiro–Wilk test

---

## 🔍 Analyses

1. **Depth Effect Across Treatments**
2. **Depth Effect Across Time**
3. **Depth × Treatment × Time Interaction**

Tests: Welch’s t-test, Mann–Whitney U (p-values and statistics reported).

---

## 🖥️ Usage

```bash
pip install numpy pandas scipy statsmodels seaborn matplotlib
```

Workflow: transform → check residuals → analyze depth, treatment, time, and interactions.

---

## 📊 Outputs

* Summary tables (pairwise comparisons)
* Residual plots and Q–Q plots
* Optional CSV/Excel export

---

## 📁 Folder Structure

```
soil-depth-analysis/
├── data/pH_raw_data.csv
├── notebooks/pH_analysis.ipynb
├── src/transformations.py
├── src/stats_tests.py
├── src/visualization.py
├── README.md
└── requirements.txt
```

---

## 📌 Notes

* Modular transformations
* Generalized loops for scalability
* Diagnostics ensure valid statistical inference

---

✅ Optional: `.md` summary and organized `.zip` folder of code & outputs


