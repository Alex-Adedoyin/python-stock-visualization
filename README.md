# 📈 Diversified Stock Price Analysis (2015–2025)

Welcome to a data-driven exploration of historical price movements across a diversified portfolio of 10 leading U.S. tech stocks, benchmarked against the S&P 500 Index.

👉 **[Open the full analysis notebook](https://github.com/Alex-Adedoyin/python-stock-visualization/blob/main/diversified_stock_analysis.ipynb)

---

## 🧠 Project Summary

This analysis evaluates best-in-class equities across the beta spectrum from 2015 to 2025, integrating both quantitative finance principles and robust Python automation. Historical data is sourced programmatically from yfinance, ensuring accuracy and replicability.

Prices are normalized (indexed to 1) for cross-comparability, enabling meaningful performance benchmarking across assets with differing nominal price levels. NVIDIA’s exceptional growth trajectory is treated as a case study in outlier behavior, with dual visualizations—both inclusive and exclusive—to prevent distortion in peer performance analysis.

A portfolio-level correlogram is generated to quantify diversification benefits, identify co-movement patterns, and highlight optimal combinations for risk-adjusted returns. The final deliverable bridges the gap between data science and investment insight, serving both technical and market-facing stakeholders.

---

## 📊 Features

- ✅ Data sourced via `yfinance`  
- ✅ Price normalization for clean comparison  
- ✅ Interactive visualizations using Plotly (dark/light themes)  
- ✅ Optional exclusion of outlier (NVIDIA) to improve contrast  
- ✅ Heatmap of daily return correlations  
- ✅ Histogram & distribution plots for returns  
- ✅ Reusable and well-commented modular Python functions

---

## 📂 Repository Contents

- 📘 `Diversified_Stock_Analysis.ipynb` – **Main notebook** with full code, analysis, and charts  
- 📎 `*.png` files – Static versions of key interactive charts (for quick view on GitHub)  
- 🔗 `*.html` files – Full interactive Plotly charts (openable via GitHub Pages)  
- 📄 `requirements.txt` – Full list of Python dependencies  

---

## 🌐 Interactivity Note

GitHub may not display interactive Plotly charts. For each Plotly chart:

- A **static PNG version** is displayed for quick preview.  
- A **link to the interactive HTML version** is provided:  

  > _“If you're viewing this notebook on a platform that doesn't support Plotly interactivity, please [click here](Interactive_Distribution_Plot.html) to view the chart in full.”_

---

## 💻 Tools & Libraries

- Python  
- `pandas`, `numpy`, `yfinance`  
- `matplotlib`, `seaborn`  
- `plotly.express`, `plotly.graph_objects`, `plotly.io`

---

## 🧰 Setup Instructions

1. Clone this repository or download the files manually  
2. Install required packages via:

```bash
pip install -r requirements.txt
```

---

## 📇 Author

**Adedoyin Adeyemi Ojo**  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/adedoyinadeyemi)
