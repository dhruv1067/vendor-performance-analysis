# 📊 Vendor Performance Analysis | End-to-End Data Analytics Project

An end-to-end data analytics project that analyzes vendor performance, inventory efficiency, profitability, and purchasing behavior using Python, SQL-style data analysis, and Power BI.

The project processes large-scale retail transaction data to uncover actionable business insights that help optimize inventory management, vendor relationships, pricing strategies, and profitability. The analysis focuses on identifying underperforming brands, evaluating vendor dependency, measuring inventory turnover, and validating business hypotheses through statistical analysis. The business objectives include improving inventory efficiency, reducing vendor risk, and increasing sustainable profitability. :contentReference[oaicite:0]{index=0}

---

## 🚀 Project Overview

This project answers several important business questions:

- Which vendors contribute the most to sales and gross profit?
- Which brands require promotional or pricing adjustments?
- Does bulk purchasing reduce unit cost?
- Which vendors have slow-moving inventory?
- Are profit margins significantly different between high-performing and low-performing vendors?
- How can inventory and purchasing strategies be optimized?

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Power BI
- Jupyter Notebook

---

## 📂 Dataset

The original project was built using approximately **2 GB** of retail transaction data.

Due to GitHub file size limitations, the large transaction datasets (`sales.csv` and `purchases.csv`) are not included in this repository. Samples of those datasets are included.

Included datasets:

- purchases_sample.csv
- sales_sample.csv 
- begin_inventory.csv
- end_inventory.csv
- purchase_prices.csv
- vendor_invoice.csv
- vendor_sales_summary.csv

---

## 📋 Data Preparation

The following preprocessing steps were performed:

- Data cleaning
- Missing value handling
- Duplicate removal
- Feature engineering
- Vendor-level aggregation
- Inventory calculations
- Profitability calculations
- Stock turnover calculations

To improve analysis quality, transactions with non-positive gross profit, non-positive profit margin, and zero sales quantity were filtered before performing the final analysis.

---

## 📊 Dashboard Preview

### Executive Dashboard

images/dashboard1.png

---

## 📈 Key Insights

### 📌 Vendor Dependency

- Top 10 vendors account for **65.69%** of total purchases, highlighting a significant dependency on a small number of suppliers. Diversifying vendor partnerships could reduce supply chain risk.

### 📌 Bulk Purchasing

- Bulk purchasing reduces unit cost by approximately **72%**, demonstrating clear economies of scale and supporting larger purchase orders where appropriate.

### 📌 Inventory Management

- Approximately **$2.71M** of inventory remains unsold, indicating opportunities to optimize purchasing, reduce holding costs, and improve cash flow.

### 📌 Promotional Opportunities

- **198 brands** exhibit low sales but high profit margins, suggesting they could benefit from targeted promotions or pricing adjustments to increase sales volume without sacrificing profitability.

### 📌 Profitability Analysis

Statistical hypothesis testing confirmed a significant difference in profit margins between high-performing and low-performing vendors, indicating distinct profitability models and opportunities for different optimization strategies.

---

## 📉 Business Recommendations

- Re-evaluate pricing for low-sales, high-margin brands.
- Diversify vendor partnerships.
- Increase bulk purchasing where economically beneficial.
- Improve management of slow-moving inventory.
- Strengthen marketing and distribution strategies for low-performing vendors.

---

## 📌 Future Improvements

- Build an interactive web application using Streamlit.
- Automate data refresh pipelines.
- Integrate SQL Server or PostgreSQL.
- Add predictive demand forecasting models.
- Deploy the dashboard online.

---

## 👨‍💻 Author

**Dhruv**

Chemical Engineering Undergraduate | Data Analytics Enthusiast
