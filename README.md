# 📊 Bitcoin Price Analysis

This project analyzes the historical price and volume of Bitcoin over the last 12 months using Python and Jupyter Notebook.

## 📁 Files Included
- `Bitcoin_Price_Analysis.ipynb`: Jupyter Notebook with full analysis
- `Bitcoin Historical Data.csv`: Original Bitcoin price and volume data (from Yahoo Finance)

## 🧪 Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔍 Analysis Overview
- Daily closing price line chart
- Daily volatility (High - Low)
- Correlation between volume and price
- Monthly average price trend
- Top 5 days by volatility and volume

## 📈 Key Insights
- Weak positive correlation between volume and price (~0.14)
- Highest volatility observed on 2024-12-05 (~$11,209)
- Price dropped in March 2025, then rebounded in May and June

## ✅ How to Use
1. Clone or download this repository
2. Place the CSV file inside a `data/` folder (optional)
3. Open the `Bitcoin_Price_Analysis.ipynb` notebook in JupyterLab or Jupyter Notebook
4. Install the required libraries if needed:
```bash
pip install pandas matplotlib seaborn
```

---

_Data Source: [Yahoo Finance - BTC/USD Historical Prices](https://finance.yahoo.com/quote/BTC-USD/history/)_