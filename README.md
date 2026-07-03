# 🛒 E-Commerce Sales Analysis

An end-to-end **E-Commerce Sales Analysis** project built using **Python, Pandas, Matplotlib, Seaborn, Plotly, and Power BI**. This project analyzes the **UCI Online Retail II Dataset** to uncover actionable business insights through data cleaning, exploratory data analysis (EDA), customer segmentation, and interactive dashboards.

---

## 📌 Project Overview

This project simulates a real-world business analytics workflow by transforming raw transactional data into meaningful insights. The dataset contains over 500,000 retail transactions from a UK-based online retailer, making it an excellent case study for data analysis and business intelligence.

The project demonstrates the complete analytics lifecycle, including:

* Data Collection
* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Business KPI Analysis
* Customer Segmentation
* Product Performance Analysis
* Interactive Data Visualization
* Business Recommendations

---

## 📊 Dataset

**Dataset:** UCI Online Retail II Dataset

The dataset contains transactional records of an online retail store, including:

| Column      | Description             |
| ----------- | ----------------------- |
| Invoice     | Invoice Number          |
| StockCode   | Product Code            |
| Description | Product Name            |
| Quantity    | Quantity Purchased      |
| InvoiceDate | Transaction Date & Time |
| Price       | Unit Price              |
| Customer ID | Customer Identifier     |
| Country     | Customer Country        |

---

## 🎯 Objectives

* Clean and preprocess raw transaction data.
* Analyze customer purchasing behavior.
* Identify top-performing products.
* Discover revenue trends.
* Analyze country-wise sales.
* Perform customer segmentation using RFM Analysis.
* Estimate Customer Lifetime Value (CLV).
* Conduct Cohort Analysis.
* Categorize products using ABC Analysis.
* Build interactive dashboards for business decision-making.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Jupyter Notebook
* Power BI
* Tableau
* Git & GitHub

---

## 📂 Project Structure

```text
Ecommerce-Sales-Analysis/
│
├── data/
│   └── online_retail_II.csv
│
├── notebooks/
│   └── Ecommerce_Analysis.ipynb
│
├── dashboard/
│   ├── Ecommerce_Dashboard.pbix
│   └── Tableau_Dashboard.twbx
│
├── images/
│
├── reports/
│   └── Business_Report.pdf
│
├── requirements.txt
├── README.md
└── ecommerce_analysis.py
```

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

* Removed missing values
* Removed duplicate records
* Converted InvoiceDate to datetime format
* Removed cancelled invoices
* Removed returned products
* Removed free items
* Removed invalid quantities
* Created Revenue feature
* Corrected data types

---

## 📈 Exploratory Data Analysis

The analysis includes:

* Dataset Overview
* Missing Value Analysis
* Revenue Distribution
* Country-wise Revenue
* Monthly Revenue Trend
* Daily Sales Trend
* Hourly Sales Trend
* Customer Distribution
* Product Distribution
* Sales Heatmaps

---

## 📊 Key Performance Indicators (KPIs)

* Total Revenue
* Total Orders
* Total Customers
* Average Order Value
* Average Basket Size
* Total Products Sold

---

## 📉 Visualizations

This project includes multiple business visualizations such as:

* Top 10 Countries by Revenue
* Monthly Revenue Trend
* Revenue Distribution
* Daily Sales Analysis
* Hourly Sales Analysis
* Weekday Sales Pattern
* Top Selling Products
* Top Customers
* Country-wise Sales
* Product Performance
* Customer Spending Distribution
* Pareto Analysis (80/20 Rule)

---

## 👥 Customer Analytics

### RFM Segmentation

Customers are classified into:

* Champions
* Loyal Customers
* Potential Loyalists
* New Customers
* At Risk
* Can't Lose Them
* Hibernating
* Lost Customers

---

## 💰 Customer Lifetime Value (CLV)

The project estimates customer lifetime value using:

* Purchase Frequency
* Average Order Value
* Customer Revenue
* Estimated Lifetime Value

---

## 📦 ABC Product Analysis

Products are categorized into:

* **A Class:** Top 80% Revenue
* **B Class:** Next 15% Revenue
* **C Class:** Remaining 5% Revenue

---

## 📅 Cohort Analysis

Customer retention is analyzed using monthly cohorts to understand repeat purchasing behavior and long-term customer engagement.

---

## 📊 Dashboard

The Power BI dashboard provides:

* Executive KPIs
* Revenue Trends
* Country-wise Sales
* Customer Insights
* Product Performance
* Interactive Filters
* Drill-down Reports

---

## 📌 Business Insights

Key findings from the analysis include:

* Revenue is concentrated among a small percentage of customers.
* A limited number of products contribute significantly to total sales.
* The majority of sales originate from a few countries.
* Customer purchasing behavior follows seasonal patterns.
* Repeat customers generate a substantial share of overall revenue.

---

## 🚀 Future Improvements

* Sales Forecasting
* Demand Prediction
* Recommendation System
* Customer Churn Prediction
* Profitability Analysis
* Interactive Web Dashboard using Streamlit

---

## 💻 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Ecommerce-Sales-Analysis.git
```

Navigate to the project directory:

```bash
cd Ecommerce-Sales-Analysis
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the analysis:

```bash
python ecommerce_analysis.py
```

Or open the Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📷 Preview

> Add screenshots of your notebook, visualizations, and Power BI dashboard in the `images/` folder and reference them here.

---

## 🤝 Contributing

Contributions, feature requests, and suggestions are welcome. Feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Harsh Pandey**

**Aspiring Data Analyst | AI/ML Enthusiast | Python Developer**

If you found this project useful, consider giving it a ⭐ on GitHub!
