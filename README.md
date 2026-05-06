# Machine Learning and Data Science Portfolio

**Data Science and Economics Graduate**

📍 [Singapore] · 📧 [ramasamynitya03@gmail.com] · 💼 [LinkedIn]www.linkedin.com/in/nityaramasamy

---

## Overview

Hi! I am Nitya, a recent graduate in BSc Data Science and Economics from the National University of Singapore. This repository showcases my data science projects, covering data analysis, machine learning, and data visualization.


**Core skills:**
- **Languages:** Python, Java, SQL, R
- **ML / DL:** scikit-learn, TensorFlow, PyTorch, XGBoost
- **Data & Viz:** Pandas, NumPy, Matplotlib, Seaborn, Plotly
- **Tools:** Git, Jupyter, Streamlit


---
## 📂 Project Summary

| # | Project | Domain | Techniques | Tools |
|---|---------|--------|------------|-------|
| 1 | [Predicting Credit Risk](#1-predicting-credit-risk) | Finance / Tabular | Classification, Feature Engineering, SHAP | Python, scikit-learn, Pandas |
| 2 | [Singapore HDB Resale Analytics Dashboard](#2-singapore-hdb-resale-analytics-dashboard-housingdash) | Real Estate / Analytics | EDA, SQL Aggregation, Data Visualisation | Python, Pandas, SQLite, Streamlit, Plotly |
---


## 🔬 Projects

---

### 1. Predicting Credit Risk

> **Can we predict whether a borrower will default — and explain why?**

**Problem:** Credit default is a major risk for financial institutions. The goal was to build a classification model to predict whether a loan applicant is likely to default, using a labelled dataset of borrower attributes and loan characteristics.

**Approach:**
- Preprocessed data via encoding of categorical variables and feature scaling
- Engineered additional features to improve signal quality
- Trained and compared three models: Logistic Regression, Random Forest, and AdaBoost
- Tuned hyperparameters to optimise precision/recall trade-off
- Applied SHAP values to interpret model predictions at a feature level

**Results:**
- Best model (Random Forest) achieved **ROC-AUC of 0.93**, **precision of 87.7%**, and **recall of 81.4%**
- SHAP analysis revealed **age** and **loan duration** as the strongest predictors of credit default

**Key learnings:** Balancing precision and recall matters more than raw accuracy in credit risk — a false negative (missed default) is far more costly than a false positive. SHAP made the model's reasoning transparent and defensible, which is critical in a regulated domain like finance.

📁 [Repo]([[https://github.com/yourname/credit-risk](https://github.com/Tya14/Predicting-Credit-Risk)](https://github.com/Tya14/Predicting-Credit-Risk)

---

### 2. Singapore HDB Resale Analytics Dashboard (HousingDash)

> **Interactive dashboard for exploring HDB resale trends, pricing patterns, and housing insights.**

**Problem:** HDB resale data is large and complex, making it difficult to quickly extract insights on pricing trends across towns, flat types, and time periods. The goal was to build an interactive tool for efficient exploratory data analysis and decision-making.

**Approach:**
- Built an end-to-end dashboard using **Streamlit, Pandas, and Plotly** for interactive data exploration
- Implemented a **SQL-based pipeline (SQLite)** to efficiently query and aggregate 100K+ transactions (filters, GROUP BY, time-series analysis)
- Performed data cleaning and feature engineering (date parsing, price per sqm, quarterly aggregation) to support analysis
- Optimised performance using caching and dataset truncation (2005–2012) for responsive cloud deployment

**Results:**
- Enabled real-time filtering across towns, flat types, price ranges, and floor area
- Delivered key insights via KPIs, price trends, distributions, and heatmaps
- Successfully deployed a production-ready dashboard accessible via web interface

**Key learnings:** Combining SQL with Python significantly improves performance for analytics workflows. Designing for usability (filters, layout, responsiveness) is just as important as analysis when building data products.

📁 [Repo]https://github.com/Tya14/HousingDash · 🌐 [Live Demo]https://housingdash-hfjkswgesykxjzxutwudv3.streamlit.app/

---

## 📚 Education

**[BSc Data Science and Economics]** — [National University of Singpaore] *(Graduation: June 2026)*
- Relevant coursework: Machine Learning, Statistics, Data Mining, Algorithms, 
- Thesis / Final Year Project: Investigating Shortcut Learning and Robustness in ClimateBERT for Environmental Claim Detection

---




*Last updated: [Apr 2026]*
