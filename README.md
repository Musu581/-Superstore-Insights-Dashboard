# Superstore-Insights-Dashboard

This project presents an end-to-end analysis of the popular "Sample - Superstore" dataset using Python, Power BI, and machine learning tools. It includes regression modeling, time series forecasting, NLP feedback analysis, and insightful dashboards.

---

## 📁 Contents

- **Exploratory Data Analysis**: Sales, Profit, and Discount analysis by Region, Category, etc.
- **Machine Learning**:
  - Regression Model (RandomForest) to predict Profit.
  - Time Series Forecasting (Prophet) for 60-day sales prediction.
- **NLP**: Customer feedback segmentation using spaCy.
- **Power BI Dashboard**: KPIs and global insights visualized.
- **Excel Reporting**: Region-wise sales and profit exported to Excel.

---

## 🧠 Objectives

- Explore Sales, Profit, Quantity & Discount patterns across regions, categories and time.
- Forecast future sales and identify profit drivers.
- Analyse customer feedback with Natural Language Processing (spaCy).
- Present key KPIs through an interactive Power BI report.
- Provide reusable, well‑documented notebooks and exportable Excel summaries.

---

## 📂 Repository Contents

| Path / File | Description |
|-------------|-------------|
| **`data/`** | Raw & cleaned datasets |
| **`notebooks/`** | Jupyter notebooks for EDA, ML, NLP & forecasting |
| **`reports/`** | • `powerbi_dashboard.png` – screenshot<br>• `SUPERSTORE.pbix` – Power BI file<br>• `insight_report.xlsx` – region‑wise sales & profit |
| **`README.md`** | This document |
| **`requirements.txt`** | Python dependencies |




## 🔍 Exploratory Highlights

- **Sales vs Profit** by Category, Sub‑Category & Region  
- **Discount impact** on profitability  
- **Delivery delays** & shipping trends  
- **Top / Bottom** states & products by profit

---

## 🤖 Machine‑Learning Work

### 1. Regression Model
| Item                | Detail |
|---------------------|--------|
| Target              | `Profit` |
| Features            | `Sales`, `Quantity`, `Discount` (+ engineered vars) |
| Algorithm           | **RandomForestRegressor** |
| Current RMSE        | ~ 248 |
| Next steps          | Hyper‑tune & add categorical encodings |

### 2. Time‑Series Forecast
| Item                | Detail |
|---------------------|--------|
| Library             | **Prophet** |
| Granularity         | Daily sales |
| Horizon             | 60 days |
| Outputs             | Forecast plot + trend / seasonality components |

---

## 💬 NLP (Customer Feedback)

- Sentence segmentation, tokenisation & NER via **spaCy** (`en_core_web_sm`)  
- Ready for sentiment or topic modelling extensions.

---

## 🛠️ Tech Stack

| Layer         | Tools |
|---------------|-------|
| Data Wrangling | `pandas`, `numpy` |
| Visualisation  | `matplotlib`, `seaborn`, **Power BI** |
| Modelling      | `scikit‑learn`, `prophet` |
| NLP            | `spaCy` |
| Notebook Env.  | **Jupyter** |

---


## 📦 Dataset

- File: `Sample - Superstore.csv`
- Source: [Kaggle Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

---

## 🛠️ Technologies Used

- Python: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `prophet`, `spacy`
- Power BI: Interactive dashboard and data visualization
- Jupyter Notebook for all modeling and analysis

---
##  Author
Muskan Kumari
B.Tech CSE – 3rd Year
BIT Mesra
LinkedIn | GitHub
