# 🛍️ Superstore Sales Analysis

This project analyzes sales data from a fictional Superstore to uncover trends in regional performance, product profitability, and time-based sales patterns. It showcases skills in data cleaning, aggregation, visualization, and business insight generation using Python.

---

## 📊 Objective

To:
- Explore Superstore's performance across regions and product categories
- Identify sales trends over time
- Deliver insights that can guide strategic decisions for sales and inventory planning

---

## 📁 Dataset

- **Source**: [Kaggle – Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **File**: `SampleSuperstore.csv`
- **Records**: 9,994 sales transactions
- **Key Fields**: `Order Date`, `Region`, `Sales`, `Profit`, `Category`, `Sub-Category`, `Product Name`, etc.

---

## 🧰 Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook (Anaconda)
- Encoding: ISO-8859-1 to handle special characters

---

## 📈 Analysis Overview

### 🗺️ Sales by Region
Grouped total sales by region and visualized them using a bar chart.

**Insight**:  
The **West region** generated the highest total sales, followed by the **East**.

---

### 📅 Monthly Sales Trend
Converted order dates to datetime format and resampled to analyze monthly performance.

**Insight**:  
Sales consistently trend upwards with visible peaks during the holiday season (Q4), suggesting seasonality effects.

---

### 🧾 Profit by Sub-Category
Calculated total profit by sub-category and visualized it using a horizontal bar chart.

**Insight**:  
Sub-categories such as **Tables** and **Bookcases** generate **negative profit**, indicating either high discounts or operational inefficiencies.

---

## 💡 Business Recommendations

- **Re-evaluate discount strategies** for loss-making products like Tables and Bookcases.
- **Capitalize on Q4 peaks** with seasonal campaigns and inventory planning.
- **Increase marketing investment** in the West and East regions for higher returns.

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `SampleSuperstore.csv` | Sales dataset |
| `superstore_sales_analysis.ipynb` | Python notebook with full analysis |
| `superstore_sales_analysis.pdf` | Exported notebook (read-only) |

---

## 🚀 Next Steps

Planned extensions for this project:
- Product-level forecasting using time series
- Profit margin analysis by discount brackets
- Integration with Tableau for interactive dashboards
