## 🟢 Blinkit Sales Analysis — Python EDA

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

End-to-end **Exploratory Data Analysis (EDA)** on Blinkit's grocery sales dataset using Python. Covers data cleaning, KPI calculation, and business-driven visualisations to uncover sales patterns across product types, outlet sizes, fat content, locations, and establishment years.

---
##  📸 Preview

![Blinkit Sales Analysis](Blinkit_Analysis_Preview.png)

## 📓 View Notebook

👉 [Click here to open the Jupyter Notebook](https://github.com/abhisheknirmal02-lab/-Blinkit-Sales-Analysis-Python-Exploratory-Data-Analysis-EDA-/blob/main/Blinkit%20Sales%20Analysis%20In%20Python.ipynb)

---

## 📈 KPIs Calculated

| KPI | Description |
|---|---|
| Total Sales | Overall revenue generated |
| Average Sales | Revenue per transaction |
| No. of Items Sold | Total items count |
| Average Rating | Customer satisfaction score |

---

## 📊 Charts & Visualisations

- 🥧 **Pie Chart** — Total Sales by Fat Content (Low Fat vs Regular)
- 📊 **Bar Chart** — Total Sales by Item Type (all product categories ranked)
- 📦 **Grouped Bar** — Fat Content by Outlet Location Tier (Tier 1 / 2 / 3)
- 📉 **Line Chart** — Total Sales by Outlet Establishment Year
- 🍩 **Pie Chart** — Sales by Outlet Size (Small / Medium / High)
- 📍 **Horizontal Bar** — Total Sales by Outlet Location Type

---

## 🧹 Data Cleaning

```python
# Standardised inconsistent values in Item Fat Content
df['Item Fat Content'] = df['Item Fat Content'].replace({
    'LF': 'Low Fat',
    'low fat': 'Low Fat',
    'reg': 'Regular'
})
```

---

## 🛠 Tools & Libraries

- **Python** — core programming language
- **Pandas** — data loading, cleaning, and groupby analysis
- **NumPy** — numerical operations
- **Matplotlib** — bar charts, pie charts, line charts
- **Seaborn** — horizontal bar chart for outlet location
- **Jupyter Notebook** — development environment

---

## 📂 Files

```
├── Blinkit Sales Analysis In Python.ipynb   # Jupyter Notebook
├── Blinkit Sales Analysis In Python.html    # Exported HTML version
└── blinkit_data.csv                         # Raw dataset
```

---

## 🚀 How to Run

1. Clone this repository
2. Install required libraries: `pip install pandas numpy matplotlib seaborn`
3. Open `Blinkit Sales Analysis In Python.ipynb` in Jupyter Notebook
4. Run all cells from top to bottom

---

*Built as a portfolio project to demonstrate Python-based data analysis and visualisation skills on real-world quick commerce data. ⭐ Star this repo if you find it useful!* 
