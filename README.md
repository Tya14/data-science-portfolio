# Machine Learning and Data Science Portfolio

**Data Science and Eocnomics Graduate**

📍 [Singapore] · 📧 [ramasamynitya03@gmail.com] · 💼 [LinkedIn](www.linkedin.com/in/nityaramasamy) 

---

## Overview

I'm a recent graduate in BSc Data Science and Economics from the National University of Singapore. I'm passionate about turning raw data into actionable insights and building machine learning systems that solve real-world problems. This repository showcases my data science projects, covering data analysis, machine learning, and data visualization. Each project focuses on solving real-world problems and communicating insights effectively.


**Core skills:**
- **Languages:** Python, Java, SQL, R
- **ML / DL:** scikit-learn, TensorFlow, PyTorch, XGBoost
- **Data & Viz:** Pandas, NumPy, Matplotlib, Seaborn, Plotly
- **Tools:** Git, Jupyter, Streamlit


---

## 📂 Project Summary

| # | Project | Domain | Techniques | Tools |
|---|---------|--------|------------|-------|
| 1 | [Predicting Credit Risk](#1-predicting-credit-risk) | Finance / Tabular | Classification, Feature Engineering, SHAP | Python, scikit-learn, Pandas  |
| 2 | [Singapore HDB Resale Price Prediction](#2-singapore-hdb-resale-price-prediction) | Real Estate / Geospatial | Regression, Feature Engineering, Geospatial Analysis | Python, LightGBM, GeoPandas  |
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

📁 [Repo](https://github.com/yourname/credit-risk) · 📓 [Notebook](link)

---

### 2. Singapore HDB Resale Price Prediction

> **Predicting HDB resale prices using transaction history and geospatial features.**

**Problem:** HDB resale prices in Singapore are influenced not just by flat attributes (type, floor, age) but also by location factors like proximity to MRT stations and schools. The goal was to build a regression model that captures both, helping buyers and sellers make more informed decisions.

**Approach:**
- Sourced 200,000+ historical HDB transactions from [data.gov.sg](https://data.gov.sg)
- Enriched the dataset with geospatial features — MRT distance and school proximity — using the **OneMap API** and **GeoPandas**
- Built a **LightGBM** regression model, iterating from a baseline (flat attributes only) to a full model with geospatial features

**Results:**
- Achieved **RMSE of ~$38,000** on the test set
- Adding geospatial features improved model performance by **9%** over the baseline

**Key learnings:** Geospatial feature engineering made a meaningful difference — distance to the nearest MRT station was among the most predictive features. Working with the OneMap API also gave practical experience with government data APIs and coordinate-based joins at scale.

📁 [Repo](https://github.com/yourname/hdb-price-prediction) · 📓 [Notebook](link)

---



## 📚 Education

**[BSc Data Science and Economics]** — [National University of Singpaore] *(Graduation: June 2026)*
- Relevant coursework: Machine Learning, Statistics, Data Mining, Algorithms, 
- Thesis / Final Year Project: Investigating Shortcut Learning and Robustness in ClimateBERT for Environmental Claim Detection

---




*Last updated: [Apr 2026]*
