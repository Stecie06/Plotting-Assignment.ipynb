# Plotting-Assignment.ipynb

# Fuel Efficiency Analysis with Matplotlib and Seaborn

## 📌 Project Overview

This notebook is a visualization-based analysis of a fuel economy dataset, focused on exploring relationships between different vehicle attributes like engine size, fuel type, and emissions. The aim is to prepare the data for future AI applications by extracting meaningful visual insights.

The project is part of the **ASC23 assignment on Transport Systems**, specifically analyzing vehicles and fuel efficiency.

---

## 🔍 What’s Included

- ✅ Data import using Pandas
- ✅ Displayed a sample (first 8 rows) of the dataset
- ✅ Plotted a **Histogram** showing fuel efficiency distribution
- ✅ Created a **Heatmap** showing correlation between numeric features
- ✅ Each diagram is accompanied by **interpretation comments**
- ✅ Exported diagrams as PNG files (`histogram.png`, `heatmap.png`)
- ✅ Source notebook with all code and visible outputs

---

## 🧪 Libraries Used

- `pandas`  
- `matplotlib`  
- `seaborn`  
- `numpy`  

---

## 📊 Diagram Interpretations

### 🔹 Histogram: Fuel Efficiency (mpg)
Shows the distribution of miles per gallon. Most vehicles cluster around average efficiency. Few vehicles are extremely fuel-efficient or inefficient.

### 🔹 Heatmap: Correlation Matrix
Highlights relationships between numeric features. Strong correlations help identify redundant or unimportant columns, e.g.:
- `UCity` and `city` are highly correlated.
- If a column has a correlation ~1 or ~0 with others, it might be a candidate for removal.

---

## 📁 Files Included

- `fuel_econ - fuel_econ.csv` — dataset
- `fuel_analysis.ipynb` — Jupyter/Colab notebook with full analysis
- `histogram.png` — histogram export
- `heatmap.png` — heatmap export

---

## 🚀 How to Run

You can view and run this notebook in [Google Colab](https://colab.research.google.com/) or clone this repo and run it locally with:

```bash
pip install pandas seaborn matplotlib numpy