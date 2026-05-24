# Carlo Zazzarino — Data Science Portfolio

Personal portfolio of data science and analysis projects built alongside an MSc in Data Science (110/110 e Lode, Università Niccolò Cusano, 2022).

My background is IT Operations leadership — 25+ years, most recently as Regional IT Operations Manager at Bureau van Dijk across a 6-site EMEA estate. These projects reflect my applied interest in bridging IT operations with data science, statistical analysis, and machine learning.

---

## Projects

### 🔢 Numerical Predictor
**File:** `numerical_predictor.ipynb`

A complete end-to-end machine learning pipeline for predicting numerical targets from structured data.

- Data loading from CSV, URL, or demo dataset
- Preprocessing pipeline: missing value imputation, categorical encoding, feature scaling
- Three model types: Linear Regression, Ridge, Random Forest, Gradient Boosting
- Evaluation: RMSE, MAE, R² with residual plots
- Feature importance analysis
- Model export via `joblib`

**Stack:** Python · scikit-learn · Pandas · NumPy · Matplotlib · Seaborn

---

### 🎱 Lottery Statistical Analyser
**File:** `lottery_analysis.ipynb`

Statistical analysis toolkit for historical lottery draw data. Demonstrates applied probability and inferential statistics — not a prediction tool (lottery draws are random by design).

- Frequency analysis: most and least drawn numbers
- Hot and cold number detection using configurable rolling windows
- Gap analysis: draws since each number last appeared
- Chi-squared uniformity test: is the draw distribution statistically random?
- Co-occurrence analysis: pairs and triplets that appear together most often
- Monte Carlo simulation based on historical frequency weights
- Ticket scorer: evaluate any set of numbers against historical data

**Stack:** Python · Pandas · NumPy · SciPy · Matplotlib · Seaborn

---

### 📊 Data Analyzer
**File:** `data_analyzer.ipynb`

Flexible data ingestion and exploratory analysis notebook supporting multiple data sources.

- Three loading modes: local JSON file, REST API endpoint, or inline JSON string
- Automatic flattening of nested JSON structures to DataFrame
- Summary statistics, trend analysis, and distribution visualisation
- Filter and full-text search across loaded data
- Designed for quick EDA on any structured JSON dataset

**Stack:** Python · Pandas · Requests · Matplotlib · Seaborn · Tabulate

---

### ⌨️ Dev Kit
**File:** `dev_kit.html`

A personal coding standards reference application covering Python, R, and SQL best practices for side projects and personal development work.

- Python: naming conventions, module structure, type hints, docstrings, error handling, tooling (black, ruff, pyproject.toml)
- SQL: formatting standards, naming conventions, query patterns, CTEs, performance guidance, schema design
- R: coding standards and analytical workflow conventions
- Interactive browser-based app — open locally in any browser, no server required

**Stack:** HTML · CSS · JavaScript (vanilla)

---

## Tech Stack Summary

| Language / Tool | Usage |
|---|---|
| Python 3.10+ | All notebooks |
| scikit-learn | ML pipeline, preprocessing, evaluation |
| Pandas / NumPy | Data manipulation and numerical operations |
| SciPy | Statistical tests (chi-squared, distributions) |
| Matplotlib / Seaborn | Visualisation |
| Requests | REST API data ingestion |
| joblib | Model serialisation |
| HTML / CSS / JS | Dev Kit browser application |

---

## Background

- **MSc Data Science & Data Analysis** — Università degli Studi Niccolò Cusano (2022) · 110/110 e Lode
- **BSc Statistics and Actuarial Science** — Università degli Studi di Roma "La Sapienza" (1995) · 96/110
- **LinkedIn:** [linkedin.com/in/carlozazzarino](https://linkedin.com/in/carlozazzarino)

---

*All projects are personal learning and portfolio work. Notebooks are self-contained and runnable with standard Python data science dependencies.*
