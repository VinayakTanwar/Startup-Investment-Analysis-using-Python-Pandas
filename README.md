# 📊 Startup Investment Analysis using Python & Pandas

## 🔍 Project Overview
This data analysis project focuses on exploring startup financials to identify potential investment opportunities. Using Python (Pandas, Seaborn, Matplotlib), we examine a dataset containing stock market data of various startups across sectors, analyzing their market cap, valuation metrics, and performance range.

---

## 📁 Dataset Overview
The dataset includes the following key columns:
- **Name** – Company name
- **Price** – Current trading price
- **Market Cap** – Market valuation
- **Price/Earnings** – P/E ratio
- **Earnings/Share** – EPS value
- **52 Week High / Low** – Highest and lowest price in the last 52 weeks
- **Sector** – Industry sector of the company

---

## ✅ Key Insights:
- Identified **top 10 companies** with the highest market cap in each sector.
- Highlighted **undervalued companies** with P/E ratio < 15.
- Found companies trading at **52-week highs/lows** (potential breakouts or bottoms).
- Categorized companies as **Small Cap**, **Mid Cap**, and **Large Cap**.
- Created a **correlation heatmap** for numeric features.
- Filtered **high EPS stocks** and visualized trends.
- Cleaned and engineered new features like:
  - `Undervalued` (Boolean)
  - `52 Week Range` (Price spread)
  - `Market Cap Category`

---

## 📈 Tools & Technologies:
- Python 🐍
- Pandas 🐼
- Seaborn 🎨
- Matplotlib 📊
- Jupyter Notebook 📓

---

## 🧠 Skills Demonstrated:
- Data Cleaning & Feature Engineering
- Conditional Filtering
- GroupBy Aggregations
- Sorting & Indexing
- Visual Analysis (Heatmaps, Bar plots)
- Financial Interpretation

---

## 🚀 Final Outcome
This analysis helps identify potentially profitable investments by leveraging publicly available financial indicators. It provides a starting point for investors to make data-driven decisions.

---

## 📌 How to Run
1. Download the notebook file: `Startup_Investment_project_FINAL.ipynb`
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn
