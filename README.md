# Atliq-Happiness-Index-Survey

# 🧠 NumPy HR Analytics — AtliQ Employee Happiness Case Study

## 📌 Project Overview

AtliQ's HR team wanted to understand employee happiness across departments
and how tenure correlates with satisfaction. This project transforms raw 
survey data into actionable HR insights using core NumPy operations — 
no Pandas, no shortcuts.

---

## 📂 Dataset Structure

Two structured NumPy arrays:

| Array | Columns |
|-------|---------|
| `employee_details` | Employee ID, Department, Years at AtliQ |
| `survey_results` | Employee ID, Happiness Score (1–10) |

---

## 🔧 Tasks Covered

| # | Task | NumPy Concept |
|---|------|---------------|
| 1 | Merge both arrays | `np.hstack` |
| 2 | Extract happiness scores | Array slicing `[:,4]` |
| 3 | Sort scores in ascending order | `np.sort` |
| 4 | Print Employee ID & Department | Loop + indexing |
| 5 | Print ID with Happiness Score | Loop + indexing |
| 6 | Convert scores to float | `.astype(float)` |
| 7 | Calculate company-wide average | `np.mean` |
| 8 | Find unique departments | `np.unique` |
| 9 | Calculate HR department average | Boolean indexing + `np.average` |

---

## 📊 Key Insights

- 🏢 **Company-wide Happiness Score:** 7.67 / 10
- 👥 **HR Department Score:** 8.33 / 10 — highest across all departments
- 📈 **Score Range:** 5 – 10 across 9 employees in 3 departments

---

## 💡 Key Concepts Demonstrated

- Multi-array merging with `np.hstack`
- Boolean indexing for department-level filtering
- Type conversion for numerical operations
- Aggregation functions — `np.mean`, `np.average`, `np.unique`
- Structured iteration for formatted output

---

## 🛠 Tech Stack

![Python](https://img.shields.io/badge/Python-3.10-blue)
![NumPy](https://img.shields.io/badge/NumPy-1.x-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-yellow)

---

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/your-username/numpy-hr-analytics.git

# Install dependencies
pip install numpy jupyter

# Launch notebook
jupyter notebook numpy_exercise.ipynb
```

---

## 👤 Author

**Ankur Vashistha**
Certified Data Analyst | SQL • Python • Power BI • Tableau

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/ankur-vashistha/)
