# 📊 Financial Sample Dashboard

A Python-based financial data analysis and visualization project built using **Pandas** and **Matplotlib**.

## 📁 Dataset
- **Source:** Financial Sample Dataset
- **Size:** 700 rows × 16 columns
- **Fields:** Segment, Country, Product, Discount Band, Units Sold, 
  Manufacturing Price, Sale Price, Gross Sales, Discounts, 
  Sales, COGS, Profit, Date, Month, Year

## 📈 Dashboard Visuals
The notebook generates a full **Financial Dashboard** with 5 charts:

| Chart | Description |
|-------|-------------|
| 📉 Monthly Sales Trend | Line chart showing sales performance over time |
| 🏢 Sales by Segment | Horizontal bar chart across business segments |
| 🌍 Sales by Country | Pie chart showing country-wise revenue share |
| 💰 Profit by Product | Horizontal bar chart of profit per product |
| 🏷️ Sales by Discount Band | Bar chart showing impact of discount tiers |

## 🔢 KPI Summary
The dashboard displays key business metrics at a glance:
- ✅ Total Sales
- ✅ Total Profit
- ✅ Total Units Sold
- ✅ Profit Margin %

## 📦 Output Files
- `financial_dashboard.png` — saved dashboard image (150 DPI)
- `financial_summary.xlsx` — exported Excel file with 5 sheets:
  - Monthly Sales, By Segment, By Country, Product Profit, Discount Band

## 🛠️ Tech Stack
- Python 3.11
- Pandas
- Matplotlib
- OpenPyXL

## 🚀 How to Run
```bash
pip install pandas matplotlib openpyxl
jupyter notebook Financial_Sample.ipynb
```

## 📂 Project Structure
```
├── Financial_Sample.ipynb   # Main notebook
├── financial_dashboard.png  # Output dashboard image
├── financial_summary.xlsx   # Output Excel summary
└── README.md
```
