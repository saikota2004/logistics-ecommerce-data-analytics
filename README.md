# Logistics & E-Commerce Data Analytics Project

## Project Overview

This project analyzes a logistics and e-commerce database using MySQL, Python, Pandas, Matplotlib, and Jupyter Notebook.

The objective is to analyze sales, customers, products, deliveries, warehouses, inventory, payments, returns, suppliers, and employees to generate meaningful business insights.

## Dataset

The database contains 11 relational tables:

- 600 Orders
- 50 Customers
- 2,203 Order Items
- 30 Products
- 600 Payments
- 600 Deliveries
- 150 Returns
- 300 Inventory Records
- 10 Warehouses
- 30 Employees
- 10 Suppliers

## Key KPIs

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

## Analysis Performed

### Sales & Revenue
- Monthly revenue analysis
- Average order value
- Order value segmentation
- Revenue by product category
- Top products by revenue

### Customer Analysis
- Customer spending analysis
- Top customers
- Customer value segmentation
- Customer order behavior

### Logistics & Delivery
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

### Returns & Payments
- Return reasons
- Returns by category
- Refund analysis
- Payment method analysis
- Payment status analysis

### Geographic & Time Analysis
- Revenue by city
- Revenue by state
- Orders by day of week
- Monthly orders and average order value

## Visualizations

The project includes visualizations for:

- Monthly Revenue
- Top 10 Products by Revenue
- Revenue by Category
- Top 10 Customers by Spending
- Delivery Performance
- Revenue by Order Value Segment
- Revenue by Customer Value Segment
- Returns by Category
- Payment Status
- Revenue by Warehouse
- Inventory Value by Supplier
- Project KPI Overview

## Tools & Technologies

- MySQL
- MySQL Workbench
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQLAlchemy
- PyMySQL
- Jupyter Notebook
- Excel

## Project Structure

```text
Logistics_ecommerce/
│
├── Logistics_Ecommerce_Data_Analytics.ipynb
├── README.md
│
├── sql/
│   └── warehouse_project.sql
│
├── data/
│   └── logistics_ecommerce_analysis.xlsx
│
└── images/