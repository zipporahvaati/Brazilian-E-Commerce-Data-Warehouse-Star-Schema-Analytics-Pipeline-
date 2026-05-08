# Brazilian-E-Commerce-Data-Warehouse-Star-Schema-Analytics-Pipeline-
## 🧠 Overview

This project builds a complete analytical data warehouse using a Brazilian e-commerce dataset.  
It transforms raw transactional CSV data into a structured **Star Schema model** using Python (Pandas).

The goal is to enable scalable business analytics such as:
- Revenue tracking
- Customer segmentation
- Product performance analysis
- Seller evaluation
- Order lifecycle insights

---

## 🏗️ Data Architecture

The system follows a **Star Schema design**:

### ⭐ Fact Table
- `fact_order_items`
- Grain: 1 row = 1 product purchased in an order
- Contains measurable business metrics:
  - price
  - freight value
  - payment value
  - review score

### 📦 Dimension Tables
- `dim_customers` → customer information & location
- `dim_products` → product catalog details
- `dim_sellers` → seller information
- `dim_orders` → order lifecycle & timestamps

---

## ⚙️ Tech Stack

- Python
- Pandas
- Google Colab
- Google Drive
- Data Modeling (Star Schema)

---

## 🔄 Pipeline Steps

1. Data ingestion from raw CSV files
2. Data cleaning and preprocessing
3. Star schema design (fact + dimensions)
4. Aggregation of payments and reviews
5. Construction of analytics-ready dataset

---

## 📈 Business Use Cases

- Sales and revenue analysis
- Customer behavior insights
- Product category performance
- Seller performance evaluation
- Order delivery tracking
- Business KPI reporting

---

## 🧱 Project Structure
