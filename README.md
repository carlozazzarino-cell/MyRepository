# Carlo Zazzarino — Data Science Portfolio

Personal portfolio of data science and analysis projects built alongside a Master di I livello in Data Analyst (110/110 e Lode, Università Niccolò Cusano, 2022).

My background is IT Operations — 25+ years, most recently as IT Operations Lead / Regional Site Lead at Bureau van Dijk across a 6-site EMEA estate. These projects reflect my applied interest in bridging IT operations with data science, statistical analysis, and machine learning.

---

## 🚀 Interactive Applications

### 🔍 DataLens — Smart Data Analysis
**File:** `data-analyzer.html`

A modern, browser-based data analysis platform with file upload capabilities and AI-powered insights. Upload CSV or Excel files and instantly get:
- Automatic data profiling (rows, columns, data types)
- Interactive charts: distributions, scatter plots, correlation heatmaps
- Column-by-column statistical summaries
- AI-powered data insights powered by Claude
- Natural language interface — ask questions about your data
- Full data preview with filtering

**Tech Stack:** HTML · CSS · JavaScript · Chart.js · PapaParse · XLSX · Anthropic API

**How to use:** Open `data-analyzer.html` in any web browser. No installation required.

---

### ⌨️ Dev Kit — Coding Standards & Number Oracle
**File:** `dev_kit.html`

A personal coding standards reference and playful number oracle application:

**Coding Standards Section:**
- **Python:** Naming conventions, module structure, type hints, docstrings, error handling, tooling (black, ruff, pyproject.toml)
- **SQL:** Formatting standards, naming conventions, query patterns, CTEs, performance guidance, schema design

**Number Oracle Section:**
- Interactive lottery number generator (SuperEnalotto, Classic 6/49, EuroMillions)
- AI-powered narrative generation explaining cosmic reasoning for selected numbers
- Entertainment purposes only

**Tech Stack:** HTML · CSS · JavaScript · Anthropic API

**How to use:** Open `dev_kit.html` in any web browser.

---

### 📚 Python · R · SQL — Interactive Textbook
**File:** `python_r_sql_book.html`

A comprehensive 20-chapter interactive textbook covering the complete data science stack:

**Part I — Python (9 chapters)**
- Getting started, variables & types, control flow, functions, data structures, files & modules
- NumPy & Pandas for data manipulation
- Matplotlib & Seaborn for visualisation
- scikit-learn for machine learning

**Part II — R (7 chapters)**
- Vectors and data types
- Control flow and functions
- Data frames and the Tidyverse
- ggplot2 for statistical graphics
- Statistical analysis and modelling

**Part III — SQL (4 chapters)**
- Foundations, data types, SELECT queries
- JOINs and relationships
- Aggregation and grouping
- Advanced SQL: CTEs, window functions, performance

**Interactive features:**
- Syntax-highlighted code blocks with copy buttons
- Clickable table of contents with progress tracking
- Practical exercises for each chapter
- Language comparison tables

**Tech Stack:** HTML · CSS · JavaScript · Highlight.js

**How to use:** Open `python_r_sql_book.html` in any web browser.

---

## 📓 Data Science Notebooks

### 🔢 Numerical Predictor
**File:** `numerical_predictor.ipynb`

A complete end-to-end machine learning pipeline for predicting numerical targets from structured data.

- Data loading from CSV, URL, or demo dataset (California Housing)
- Exploratory data analysis: distributions, correlations, scatter plots
- Preprocessing pipeline: missing value imputation, categorical encoding, feature scaling
- Train/test split (configurable)
- Three model types: Linear Regression, Random Forest, Gradient Boosting
- Model evaluation: RMSE, MAE, R² with residual plots
- Cross-validation (5-fold)
- Feature importance analysis
- Batch predictions on test set
- Model export via `joblib`

**Stack:** Python · scikit-learn · Pandas · NumPy · Matplotlib · Seaborn · Joblib

**How to use:** Run in Jupyter Notebook or JupyterLab. Requires: `pip install scikit-learn pandas matplotlib seaborn joblib`

---

### 📊 Data Analyzer
**File:** `data_analyzer.ipynb`

Flexible data ingestion and exploratory analysis notebook supporting multiple data sources.

- Three loading modes: local JSON file, REST API endpoint, or inline JSON string
- Automatic flattening of nested JSON structures to DataFrame
- Summary statistics, trend analysis, and distribution visualisation
- Filter and full-text search across loaded data
- Correlation analysis and heatmaps
- Flexible column selection and data manipulation
- Designed for quick EDA on any structured JSON dataset

**Stack:** Python · Pandas · Requests · Matplotlib · Seaborn · Tabulate

**How to use:** Run in Jupyter Notebook. Requires: `pip install requests matplotlib seaborn pandas tabulate`

---

### 🎱 Lottery Statistical Analyser *(Optional: not yet included)*
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

## Tech Stack Summary

| Language / Tool | Usage |
|---|---|
| **Python 3.10+** | All notebooks |
| **scikit-learn** | ML pipeline, preprocessing, evaluation |
| **Pandas / NumPy** | Data manipulation and numerical operations |
| **SciPy** | Statistical tests (chi-squared, distributions) |
| **Matplotlib / Seaborn** | Data visualisation |
| **Requests** | REST API data ingestion |
| **joblib** | Model serialisation |
| **HTML / CSS / JS** | Interactive browser applications |
| **Chart.js** | Browser-based charting |
| **Anthropic API** | AI-powered insights |

---

## Background

- **MSc Data Science & Data Analysis** — Università degli Studi Niccolò Cusano (2022) · 110/110 e Lode
- **BSc Statistics and Actuarial Science** — Università degli Studi di Roma "La Sapienza" (1995) · 96/110
- **LinkedIn:** [linkedin.com/in/carlozazzarino](https://linkedin.com/in/carlozazzarino)

---

## Getting Started

### For Interactive Applications:
1. Clone or download the repository
2. Open any `.html` file directly in your web browser
3. No installation required — works offline

### For Jupyter Notebooks:
1. Install Jupyter: `pip install jupyter`
2. Navigate to the repository folder: `cd MyRepository`
3. Start Jupyter: `jupyter notebook`
4. Open the desired notebook and run cells sequentially
5. Install dependencies as prompted: `pip install scikit-learn pandas matplotlib seaborn`

### For Development:
- Python environment: `python -m venv venv` 
- Activate: `source venv/bin/activate` (Unix) or `venv\Scripts\activate` (Windows)
- Install all dependencies: `pip install scikit-learn pandas matplotlib seaborn joblib requests`

---

*All projects are personal learning and portfolio work. Applications are self-contained and runnable with standard dependencies. Notebooks are designed for educational purposes and professional development.*
