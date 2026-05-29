# E-Commerce Sales & Customer Analytics using Python

## 📌 Project Overview

This project presents a comprehensive analysis of the **Olist Brazilian E-Commerce Dataset** using **Python, Pandas, NumPy, Matplotlib, and Seaborn**. The objective is to uncover business insights related to sales performance, customer behavior, product demand, payment preferences, seller performance, and regional trends.

The analysis follows a real-world data analytics workflow, including data cleaning, data integration, exploratory data analysis (EDA), visualization, and business recommendations.

---

## 🎯 Objectives

* Analyze sales and revenue trends over time.
* Identify top-performing product categories.
* Understand customer purchasing behavior.
* Evaluate seller performance.
* Analyze payment methods and order statuses.
* Discover regional sales patterns.
* Generate actionable business insights.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📂 Dataset

The project uses the **Brazilian E-Commerce Public Dataset by Olist** from Kaggle.

Dataset contains:

* Customers
* Orders
* Products
* Sellers
* Payments
* Reviews
* Product Categories

**Dataset Link:**
[https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

## 📊 Data Analysis Workflow

### 1. Data Collection

Loaded multiple CSV datasets containing customer, order, payment, seller, and product information.

### 2. Data Cleaning

* Checked missing values
* Verified data types
* Converted timestamps into datetime format
* Removed inconsistencies

### 3. Data Integration

Merged multiple datasets into a single master dataframe using common keys such as:

* customer_id
* order_id
* product_id

### 4. Exploratory Data Analysis (EDA)

Performed descriptive and visual analysis to identify patterns and trends.

---
## 🔍 Key Insights

* Most orders were successfully delivered, indicating strong operational efficiency.
* Credit cards emerged as the most preferred payment method.
* Certain states contributed significantly more revenue than others.
* Product categories such as electronics, home goods, and furniture generated substantial revenue.
* Monthly sales exhibited clear growth and seasonal fluctuations.
* A small number of sellers contributed a large portion of total revenue.
* Customer spending patterns varied considerably across product categories.

---

## 💡 Business Recommendations

* Focus marketing efforts on high-revenue states.
* Strengthen relationships with top-performing sellers.
* Promote high-margin product categories.
* Optimize logistics in regions with higher freight costs.
* Design promotional campaigns around peak purchasing days.
* Improve support for less popular payment methods to increase customer convenience.

---

## 📁 Project Structure

```text
E-Commerce-Sales-Analytics/
│
├── data/
│   ├── olist_customers_dataset.csv
│   ├── olist_orders_dataset.csv
│   ├── olist_order_items_dataset.csv
│   ├── olist_products_dataset.csv
│   ├── olist_order_payments_dataset.csv
│
├── images/
│   ├── order_status_distribution.png
│   ├── monthly_sales_trend.png
│   ├── correlation_heatmap.png
│   └── ...
│
├── notebooks/
│   └── E_Commerce_Analysis.ipynb
│
├── README.md
└── requirements.txt
```

---

## 🚀 Future Enhancements

* Customer Segmentation (RFM Analysis)
* Customer Lifetime Value (CLV)
* Sales Forecasting
* Interactive Dashboard using Power BI/Tableau
* Customer Review Sentiment Analysis

---

## 👨‍💻 Author

**Anushree Lal**

through all 15, but they do notice a few well-chosen visualizations.

