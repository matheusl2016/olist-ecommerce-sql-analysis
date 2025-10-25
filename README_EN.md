# Olist E-commerce Data Analysis (SQL + Python)

> **Comprehensive data analysis of brazilian e-commerce platform — Olist.**  
> SQL was used for data manipulation and exploration, while Python handled visualization and insights generation.  
> Public dataset available on [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data).

---

## 📊 Overview

This project analyzes over **100,000 real orders** from **Olist**, a Brazilian marketplace that connects small merchants to major online retail platforms.  
The goal was to **extract actionable business insights** about customer behavior, logistics performance, and profitability.

By combining **advanced SQL queries** with **Python-based visualization**, this project demonstrates how data-driven decision-making can optimize logistics, improve customer experience, and reveal long-term growth opportunities.

---

## 🎯 Objectives

- 🧾 Understand sales behavior and top-performing product categories  
- 🚚 Analyze delivery times and logistics efficiency by region  
- ⭐ Assess customer satisfaction based on review patterns  
- 💰 Calculate the **Customer Lifetime Value (CLV)** across Brazil  
- 📈 Identify sales trends and seasonality patterns  
- 🧮 Showcase end-to-end analytical thinking using SQL + Python  

---

## ⚙️ Tools and Technologies

| Technology | Purpose |
|-------------|----------|
| 🐍 **Python** | Data analysis and visualization |
| 🗄️ **SQLite + SQL** | Querying and data manipulation |
| 📘 **Jupyter Notebook** | Analytical storytelling and documentation |
| 📊 **Pandas / Matplotlib / Seaborn** | Data cleaning and visual analytics |
| 🗺️ **Folium** | Interactive geographic mapping |
| 📈 **NumPy / Squarify** | Statistics and advanced plots |

---

## 📂 Repository Structure
📂 olist-ecommerce-sql-analysis/


├── 📜 README.md ← Project overview (PT-BR)
├── 📜 README_EN.md ← English version
├── 📔 olist_analysis.ipynb ← Full Jupyter notebook
├── 🐍 sql_olist_e_commerce_data_analysis.py ← Python version


├── 📊 data/ ← Original Kaggle dataset
│ ├── olist_customers_dataset.csv
│ ├── olist_orders_dataset.csv
│ ├── olist_products_dataset.csv
│ └── ... (other CSV files)
│

├── 📈 images/ ← Visual outputs and graphs
│ ├── all_images.png
│ ├── image1.png
│ ├── image2.png
│ └── ... (other visuals)


└── 📁 sql_queries/ ← SQL scripts and analysis
├── sales.sql
├── logistics.sql
└── customers.sql

---

## 🔍 Key Insights

### 💸 **Sales Analysis**
- Top categories: **Health & Beauty** and **Electronics**.  
- Average order value (**AOV**) ≈ **R$160**, with a wide distribution.  
- Sales are concentrated in **São Paulo** and **Rio de Janeiro**.  

### 🚚 **Delivery & Logistics**
- Average delivery time: **5–12 days**, depending on the city.  
- Peaks of delay during **Christmas** and **Carnival** seasons.  
- Southeast region shows the most efficient shipping times.  

### ⭐ **Customer Reviews**
- Majority of reviews are **positive (4–5 stars)**.  
- Negative comments mostly relate to **shipping delays**, not product quality.  

### 💰 **Customer Lifetime Value (CLV)**
- CLV concentration is highest in **Southeast and South Brazil**.  
- Interactive map highlights high-value customers around **São Paulo and Rio**.  
- Average customer lifespan (TMVC): **8–12 weeks**.  

### 🛍️ **Seller Insights**
- **85%** of sellers are small businesses with <100 orders.  
- Only **2%** of sellers exceed 1000 orders.  
- Larger sellers tend to have **slower deliveries** on average.  

---

🧩 Analytical Focus

This project showcases how SQL and Python complement each other in data analysis:
SQL handles data extraction and transformation, while Python provides flexible visualization and modeling capabilities.

Complex SQL queries (CTEs, window functions, subqueries) were used to perform advanced analytics directly in the database.
Python was then used to visualize, validate, and communicate the results — turning raw data into actionable business insights.

💼 Conclusion

Through this exploration of the Olist E-commerce Dataset, we discovered:

- Sales growth driven by seasonality and regional concentration

- Strong dependence on logistics performance for customer satisfaction

- CLV concentration around Brazil’s most urbanized states

- Small sellers dominating the platform, yet facing scalability challenges

