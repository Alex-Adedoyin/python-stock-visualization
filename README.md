# 📈 Diversified Stock Price Analysis (2015–2025)

Welcome to a data-driven exploration of historical price movements across a diversified portfolio of 10 leading U.S. tech stocks, benchmarked against the S&P 500 Index.

👉 **[Open the full analysis notebook](Diversified_Stock_Analysis.ipynb)**

---

## 🧠 Project Summary

This project analyzes stock prices from 2015 to 2025. Prices are normalized (indexed to 1) to make comparisons meaningful across companies with different nominal price levels.

Special attention is given to **NVIDIA’s outlier performance**, with separate visualizations including and excluding the stock, so that other companies’ growth isn’t visually compressed.

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
