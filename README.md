# 📊 Unemployment Analysis in India — Labour Pulse Dashboard

An end-to-end data science pipeline and interactive dashboard analyzing the COVID-19 lockdown's impact on unemployment across 27 Indian states & union territories.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

<br>

[![Launch Interactive Dashboard](https://img.shields.io/badge/🚀%20LAUNCH%20INTERACTIVE%20DASHBOARD-2d2d2d?style=for-the-badge)](https://pkzq5h.csb.app/)
[![GitHub Repository](https://img.shields.io/badge/GITHUB%20REPO-181717?style=for-the-badge&logo=github)](https://lnkd.in/eB4PnEpt)

---

### 📌 Project Overview

This repository hosts a data analysis pipeline and interactive web dashboard built to quantify how India's 2020 COVID-19 lockdown reshaped state-level labour markets. It covers data cleaning, exploratory analysis, statistical significance testing ($p < 0.05$), predictive modelling, and a fully interactive React dashboard for exploring state-by-state metrics.

### 📦 Dataset

* **Source:** [Unemployment in India — Kaggle](https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india)
* **Scope:** Monthly, state-wise estimates of unemployment rate, employed population, and labour participation rate for Jan–Oct 2020, covering 27 states/UTs (267 records).

---

### 🔍 Key Findings & Features

* **Statistical Validation:** Hypothesis testing ($t$-test) confirms the COVID-19 spike was statistically significant ($p < 0.05$), with national unemployment increasing by **~3.5 percentage points** overall and peaking at **23.5%** in April 2020.
* **Core Analysis:**
  * Data cleaning, column standardization, and feature engineering.
  * Time-series trend analysis with pre- vs. post-lockdown annotations.
  * Random Forest regression modeling to evaluate key economic drivers.
* **Dashboard Features:**
  * 📈 **National Trend View:** Interactive line chart highlighting the lockdown window.
  * 🗺️ **State & Zone Explorer:** Dynamic filtering across North, South, East, and West zones.
  * 📊 **COVID Impact Rankings:** Bar charts ranking states by magnitude of unemployment surge.

---

### 🛠 Tech Stack

* **Data Science & ML:** `Python`, `pandas`, `numpy`, `scikit-learn`, `statsmodels`, `matplotlib`, `seaborn`, `plotly`
* **Frontend / Dashboard:** `React.js`, `Recharts`, `Tailwind CSS`

---

### 🚀 How to Run Locally

#### **1. Data Science Environment**
```bash
# Clone the repository
git clone [https://github.com/your-username/CodeAlpha_UnemploymentAnalysis.git](https://github.com/your-username/CodeAlpha_UnemploymentAnalysis.git)
cd CodeAlpha_UnemploymentAnalysis

# Set up virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies and launch Jupyter
pip install -r requirements.txt
jupyter lab
