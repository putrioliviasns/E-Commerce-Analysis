# UCI Online Retail Data Cleaning & Revenue Analysis

> **Project URL:** https://roadmap.sh/projects/online-retail-data-cleaning

## 📌 Project Overview
This project focuses on cleaning and analyzing real transaction data from the **UCI Online Retail Dataset** (~500,000+ rows). It addresses common data quality challenges such as missing customer IDs, negative quantities (returns), and zero unit prices, followed by core business metric aggregation.

## 🔑 Key Insights & Business Findings
- **Market Concentration:** Analysis of the top 10 revenue-generating countries revealed that the **United Kingdom** dominates total sales by a massive margin, followed by international markets like the Netherlands, EIRE, and Germany.
- **Data Quality Impact:** Filtering out non-positive quantities (returns/cancellations) and missing customer identifiers prevented distorted revenue metrics and provided a clean baseline for customer behavior analysis.
- **Revenue Driver Identification:** Identifying top-performing regions enables management to optimize regional logistics, marketing spend, and inventory allocation.

## 📊 Key Highlights
- Analyzed a **10% random sample** (~50,000 records) of the transaction dataset for efficient processing.
- Cleaned missing values and filtered out invalid records.
- Engineered a primary business metric: `Revenue = Quantity * UnitPrice`.
- Visualized the **Top 10 Countries by Total Revenue** using Seaborn and Matplotlib.

## 🛠️ Tools Used
- Python 3
- Pandas & NumPy
- Matplotlib & Seaborn
- Google Colab / Jupyter Notebook

## 📁 Repository Contents
- `online_retail_analysis.ipynb` : Main data cleaning and analysis notebook
- `top_10_countries_revenue.png` : Exported bar chart visualization of top revenue countries
- `README.md` : Project documentation
- 'Online Retail.xlsx' : Dataset 
