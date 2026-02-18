# Customer Behaviour Analysis

## 📌 Project Overview
**Customer Behaviour Analysis** is a mini end-to-end data analytics project that transforms raw customer shopping data into meaningful insights using SQL for data extraction, Python for analysis, and Power BI for interactive visualization.

______________________________________________________________________________________________________________________________________________________________________________________________________________________

## 🎯 Objective
Understand customer shopping patterns and revenue drivers

Identify high-value customers and repeat buyers

Analyze the impact of discounts, shipping type, and demographics

Perform trend and segmentation analysis

Build an interactive dashboard for decision-making

_____________________________________________________________________________________________________________________________________________________________________________________________________________________

## 🗂️ Project Components

### 1️⃣ Data Source & Database (PostgreSQL)

Customer transactional data stored in PostgreSQL.

SQL used for:

Revenue analysis (gender, category, shipping type)

Discount impact evaluation

Top product identification

Customer segmentation (New, Returning, Loyal)

Month-over-Month revenue growth

Customer Lifetime Value (CLV)

Revenue contribution percentage

RFM segmentation

Weekday vs Weekend revenue comparison

Repeat buyer percentage

Revenue concentration analysis (Pareto logic)


2️⃣ **Advanced SQL Analysis Implemented**

📈 Revenue & KPI Analysis

Total revenue by gender

Average Order Value (AOV)

Revenue by subscription status

Revenue by shipping type

Payment method performance

📊 Trend Analysis

Monthly revenue growth rate (MoM%)

Weekday vs Weekend revenue comparison

👥 Customer Analytics

Customer Lifetime Value (CLV)

High-value customers identification

Repeat buyer percentage

Frequency-based segmentation

RFM segmentation (Recency, Frequency, Monetary)

🛍️ Product Performance

Top-rated products

Top 5 products by discount rate

Top 3 products per category

Repeat purchase ratio per product

**3️⃣ Data Analysis (Python – Jupyter Notebook)**

Data analysis performed using Python to further explore patterns beyond SQL.

Libraries Used:

pandas

numpy

matplotlib

seaborn

Key Steps:

Data loading from SQL export

Data cleaning & preprocessing

Handling missing values

Feature engineering

Exploratory Data Analysis (EDA)

Distribution analysis

Correlation analysis

Behavioural pattern identification

File:
Customer_Behaviour_Analysis.ipynb

**4️⃣ Data Visualization (Power BI)**

Interactive dashboard built for business storytelling.

Dashboard Highlights:

Revenue trends over time

Customer segmentation breakdown

Category contribution %

Discount impact analysis

High-value customer insights

Shipping performance comparison

File:
customer behaviour dashboard.pbix
_____________________________________________________________________________________________________________________________________________________________________________________________________________________

## 🔄 Project Workflow
1. Extract data using SQL from PostgreSQL  
2. Load and analyze data in Python  
3. Perform EDA to identify trends and patterns  
4. Generate insights from customer behaviour  
5. Build interactive Power BI dashboard  
6. Present insights visually  

_____________________________________________________________________________________________________________________________________________________________________________________________________________________

## 🛠️ Tools & Technologies
- **Database:** PostgreSQL  
- **Language:** Python  
- **IDE:** Jupyter Notebook  
- **Visualization:** Power BI  
- **Libraries:** pandas, numpy, matplotlib, seaborn  

---

## 📘 Key Learnings
End-to-end data analytics workflow

Advanced SQL (CTEs, Window Functions, Aggregations)

KPI-driven business analysis

Customer segmentation strategies

Revenue growth and retention analysis

Data storytelling with dashboards

Integration of SQL + Python + BI tools

## ▶️ How to Run the Project
1. Execute SQL queries from `postgresSQL.sql` in PostgreSQL  
2. Open and run `Customer_Behaviour_Analysis.ipynb`  
3. Review insights and analysis  
4. Open `customer behaviour dashboard.pbix` in Power BI Desktop  

---


