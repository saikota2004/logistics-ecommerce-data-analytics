# Logistics & E-Commerce Data Analytics Project

## 📌 Project Overview

This project is an end-to-end **Logistics & E-Commerce Data Analytics** project built using a relational MySQL database and analyzed with Python.

The project focuses on analyzing sales, customers, products, deliveries, warehouses, inventory, payments, returns, suppliers, and workforce data to generate meaningful business insights.

The analysis demonstrates practical skills in **SQL, Python, Pandas, data validation, exploratory data analysis (EDA), data visualization, and business KPI analysis**.

---

## 🎯 Business Objectives

The project aims to answer questions such as:

- How much revenue is generated over time?
- Which products and categories generate the most revenue?
- Who are the highest-value customers?
- How are customers segmented based on spending?
- What is the delivery performance?
- Which warehouses generate the most revenue?
- Which products require inventory attention?
- What are the major reasons for product returns?
- How are payment methods and payment statuses distributed?
- Which suppliers hold the highest inventory value?
- Is there a relationship between order value and delivery time?

---

## 🗄️ Database Overview

The project uses an 11-table relational MySQL database.

| Table | Records | Description |
|---|---:|---|
| Customers | 50 | Customer information |
| Orders | 600 | Customer orders and order values |
| Order Items | 2,203 | Products included in orders |
| Products | 30 | Product catalog |
| Payments | 600 | Payment transactions |
| Deliveries | 600 | Delivery information |
| Returns | 150 | Product return records |
| Inventory | 300 | Warehouse inventory |
| Warehouses | 10 | Warehouse information |
| Employees | 30 | Warehouse employees |
| Suppliers | 10 | Supplier information |

---

## 📊 Key KPIs

| KPI | Value |
|---|---:|
| Total Orders | 600 |
| Total Revenue | ₹12,669,712.82 |
| Average Order Value | ₹21,116.19 |
| Total Customers | 50 |
| Total Returns | 150 |
| Total Refund Amount | ₹519,188 |
| Total Deliveries | 600 |
| Average Delivery Time | 5.49 days |
| Total Products | 30 |
| Total Warehouses | 10 |
| Total Employees | 30 |
| Total Suppliers | 10 |

---

## 📈 Analysis Performed

### Sales & Revenue Analysis

- Total revenue analysis
- Monthly revenue trends
- Average Order Value (AOV)
- Order value segmentation
- Revenue by product category
- Top 10 products by revenue

### Customer Analysis

- Customer spending analysis
- Top 10 customers
- Customer value segmentation
- Orders by customer segment
- Return behavior by customer segment

### Logistics & Delivery Analysis

- Delivery performance
- Average delivery time
- Courier performance
- Warehouse revenue analysis
- Order value vs delivery time correlation

### Inventory Analysis

- Inventory availability
- Reorder-level analysis
- Inventory value by warehouse
- Supplier inventory analysis

### Returns & Refund Analysis

- Return reasons
- Returned units by category
- Refund analysis
- Product return analysis

### Payment Analysis

- Payment method distribution
- Payment status distribution
- Payment amount analysis

### Geographic & Time Analysis

- Revenue by city
- Revenue by state
- Orders by day of week
- Monthly orders
- Monthly Average Order Value

---

## 🔍 Key Findings

Some notable observations from the analysis:

- Total revenue generated across 600 orders was **₹12.67 million**.
- The average order value was approximately **₹21.1K**.
- **Home Appliances** generated the highest category revenue.
- **External Hard Drive 1TB** generated the highest product revenue.
- The highest-value customer spent approximately **₹674.8K**.
- High-value customers accounted for a substantial share of customer spending.
- The dataset recorded **600 deliveries** with an average delivery time of **5.49 days**.
- One inventory record reached its reorder level and required attention.
- **Quality Issue** was the most frequent return reason by return count.
- The correlation between order value and delivery time was approximately **0.028**, indicating a very weak linear relationship in this dataset.

> Note: The dataset is designed for portfolio and analytical practice. Some distributions are synthetic and should not be interpreted as real-world industry benchmarks.

---

## 📊 Visualizations

The project includes visualizations for:

- Monthly Revenue
- Top 10 Products by Revenue
- Revenue by Category
- Top 10 Customers by Spending
- Delivery Performance
- Revenue by Order Value Segment
- Revenue by Customer Value Segment
- Returns by Category
- Payment Status Distribution
- Revenue by Warehouse
- Inventory Value by Supplier
- Project KPI Overview

---

## 🛠️ Tools & Technologies

### Database

- MySQL
- MySQL Workbench
- SQL

### Data Analysis

- Python
- Pandas
- NumPy
- SQLAlchemy
- PyMySQL

### Visualization

- Matplotlib
- Seaborn

### Development

- Jupyter Notebook
- Git
- GitHub

### Reporting

- Microsoft Excel

---

## 📁 Project Structure

```text
logistics-ecommerce-data-analytics/
│
├── Logistics_Ecommerce_Data_Analytics.ipynb
├── README.md
│
├── data/
│   └── logistics_ecommerce_analysis.xlsx
│
├── sql/
│   └── warehouse_project.sql
│
└── screenshots/