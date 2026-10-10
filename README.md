# UCI Online Retail Data Cleaning & Revenue Analysis

## 📌 Project Overview
This project focuses on cleaning and analyzing real transaction data from the **UCI Online Retail Dataset**. It handles common real-world data issues such as missing customer IDs, negative quantities (returns), free/promotional items (zero unit prices), and calculates total revenue across countries.

## 📊 Key Highlights
- Analyzed a **10% random sample** (~50,000 records) of the original dataset.
- Cleaned missing values and filtered out non-positive quantities and prices.
- Engineered a new metric: `Revenue = Quantity * UnitPrice`.
- Visualized the **Top 10 Countries by Total Revenue** using Seaborn and Matplotlib.

## 🛠️ Tools Used
- Python 3
- Pandas
- Matplotlib & Seaborn
- Google Colab / Jupyter Notebook

## 📁 Repository Contents
- `online_retail_analysis.ipynb` : Main data cleaning and analysis notebook
- `top_10_countries_revenue.png` : Exported bar chart visualization
- `README.md` : Project documentation
