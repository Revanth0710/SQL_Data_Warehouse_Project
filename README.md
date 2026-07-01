# 📊 Data Warehouse & Analytics Project

A complete end-to-end **Data Warehouse** project built using **SQL Server** following the **Medallion Architecture (Bronze → Silver → Gold)**. This project demonstrates industry-standard data engineering practices, including ETL development, data modeling, data quality, and analytical reporting.

---

# 🏗️ Architecture

The project follows the **Medallion Architecture** consisting of three layers:

## 🟤 Bronze Layer (Raw Data)

The Bronze layer stores data exactly as received from the source systems.

- Raw CSV files
- No transformations
- Landing zone
- Historical source copy

**Source Systems**

- CRM
- ERP

---

## ⚪ Silver Layer (Cleaned Data)

The Silver layer prepares data for analytics.

### Transformations

- Data cleansing
- Standardization
- Duplicate removal
- Null handling
- Data validation
- Data integration

---

## 🟡 Gold Layer (Business Layer)

The Gold layer contains business-ready datasets modeled using a **Star Schema**.

This layer is optimized for:

- Reporting
- Dashboards
- Business Intelligence
- Analytics

---

# 📌 Project Overview

This project demonstrates the complete lifecycle of building a modern enterprise data warehouse.

The solution integrates CRM and ERP datasets into a centralized warehouse that enables analytical reporting and business decision-making.

---

# 🚀 Features

- Medallion Architecture
- SQL Server Data Warehouse
- ETL Pipelines
- Data Cleansing
- Data Standardization
- Star Schema Design
- Fact & Dimension Modeling
- SQL Analytics
- Business Reporting
- Scalable Warehouse Design

---

# 🛠️ Technology Stack

| Technology | Purpose |
|------------|---------|
| SQL Server | Data Warehouse |
| T-SQL | ETL & Analytics |
| CSV Files | Source Data |
| Git | Version Control |
| GitHub | Repository |
| Draw.io | Architecture Diagram |

---

# 📂 Repository Structure

```text
Data-Warehouse-Analytics/
│
├── datasets/
│   ├── crm/
│   └── erp/
│
├── docs/
│   ├── architecture.md
│   ├── data-model.md
│   └── requirements.md
│
├── scripts/
│   ├── bronze/
│   ├── silver/
│   ├── gold/
│   └── analytics/
│
├── images/
│   └── data-architecture.png
│
├── README.md
└── LICENSE
```

---

# 🔄 ETL Workflow

```text
CSV Files
     │
     ▼
Bronze Layer
(Raw Tables)
     │
     ▼
Silver Layer
(Cleaned & Standardized)
     │
     ▼
Gold Layer
(Fact & Dimension Tables)
     │
     ▼
Analytics & Reporting
```

---

# 📥 Data Sources

The warehouse integrates data from two business systems.

### CRM

- Customer Information
- Sales Representatives
- Customer Details

### ERP

- Orders
- Products
- Sales
- Inventory

All datasets are provided as CSV files.

---

# ⭐ Data Model

The Gold layer follows a **Star Schema**.

```text
                 DimCustomer
                      │
                      │
DimProduct ─── FactSales ─── DimDate
                      │
                DimSalesperson
```

---

# 📊 Analytics

The warehouse supports business reporting for:

## Customer Analytics

- Customer Segmentation
- Customer Lifetime Value
- Top Customers

## Product Analytics

- Best Selling Products
- Revenue by Category
- Product Performance

## Sales Analytics

- Monthly Sales
- Quarterly Sales
- Regional Sales
- Sales Trends

---

# 🎯 Business Questions

- Who are the top customers?
- Which products generate the highest revenue?
- What are the monthly sales trends?
- Which regions perform the best?
- What are the top-performing sales representatives?

---
