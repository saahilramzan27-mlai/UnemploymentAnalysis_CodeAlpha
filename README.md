# 📊 Unemployment Analysis in India (2019–2020)

**CodeAlpha Data Science Internship — Task 2: Unemployment Analysis with Python**

An end-to-end analysis of state-wise unemployment in India, quantifying the impact of the COVID-19
lockdown on labour markets across Indian states, with interactive and static visualizations plus
policy-relevant insights.

## 📁 Project Structure
```
.
├── Unemployment_Analysis_India.ipynb   # Main analysis notebook (fully executed)
├── data/
│   └── Unemployment_in_India.csv       # Raw dataset
├── requirements.txt                    # Python dependencies
└── README.md
```

## 📦 Dataset
[Unemployment in India — Kaggle](https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india)
Monthly, state-wise estimates of unemployment rate, employed population, and labour participation
rate for Jan–Oct 2020, covering 27 Indian states/UTs.

## ⚙️ Setup

```bash
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install -r requirements.txt
jupyter lab Unemployment_Analysis_India.ipynb
```

## 🔍 What's Inside

**Core Analysis**
1. **Data Cleaning** — column standardization, date parsing, whitespace/duplicate handling, feature engineering
2. **Exploratory Data Analysis** — distributions, state and zone comparisons, geographic bubble map
3. **Time-Series Trend Analysis** — national and state-level trends with lockdown annotation, month × state heatmap
4. **COVID-19 Impact Quantification** — before/after comparison, state-by-state impact ranking
5. **Correlation Analysis** — unemployment vs. labour force participation
6. **Key Insights & Policy Recommendations**

**Advanced Analysis**
7. **Statistical Significance Testing** — Welch's t-test, Mann-Whitney U test, and a bootstrap 95% confidence
   interval to formally prove the COVID-19 unemployment spike is real, not noise
8. **Outlier Detection** — IQR-based flagging of extreme state-months
9. **Predictive Modeling** — Linear Regression & Random Forest with feature-importance analysis
10. **Forecasting** — Holt linear trend model projecting near-term unemployment
11. **Choropleth Maps** — true state-boundary geographic visualization, including an animated
    month-by-month version

## 🚀 How to Reproduce
1. Download `Unemployment_in_India.csv` from the Kaggle link above (already included in `data/`).
2. Run all cells top-to-bottom in Jupyter Lab/Notebook.

## 🛠 Tech Stack
`pandas` · `numpy` · `matplotlib` · `seaborn` · `plotly` · `statsmodels`

---
Built for the **CodeAlpha Data Science Internship**. Remember to also: post your project video on LinkedIn
tagging @CodeAlpha, upload the repo as `CodeAlpha_UnemploymentAnalysis`, and submit via the internship
submission form.
