# 📊 E-Commerce Business Intelligence Dashboard

> An end-to-end Business Intelligence project built using **Microsoft Power BI** to transform raw e-commerce data into actionable business insights through interactive dashboards, data modeling, Power Query, and DAX.

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Power BI](https://img.shields.io/badge/Power%20BI-Desktop-F2C811)
![License](https://img.shields.io/badge/License-MIT-blue)

---

# 📖 Project Overview

Businesses generate massive amounts of transactional data every day, but raw data alone cannot support strategic decision-making.

This project demonstrates the complete Business Intelligence lifecycle by transforming raw e-commerce data into six interactive dashboards that help stakeholders analyze business performance, customer behavior, product sales, operational efficiency, and geographic insights.

The project follows industry-standard BI practices including:

- Data Cleaning
- Data Transformation
- Data Modeling
- Star Schema Design
- DAX Measures
- Time Intelligence
- Interactive Dashboard Design
- KPI Development
- Business Storytelling

---

# 🎯 Project Objectives

- Build a scalable Business Intelligence solution using Power BI.
- Design a Star Schema for efficient reporting.
- Develop reusable DAX measures for business KPIs.
- Create executive-level dashboards for different business stakeholders.
- Apply dashboard design best practices.
- Deliver meaningful insights through interactive visualizations.

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| Microsoft Power BI Desktop | Dashboard Development |
| Power Query | Data Cleaning & Transformation |
| DAX | Business Calculations |
| Data Modeling | Relationship Management |
| Git | Version Control |
| GitHub | Project Hosting |

---

# 📂 Dataset

The project uses four relational datasets.

| Dataset | Description |
|----------|-------------|
| Customers | Customer demographic information |
| Orders | Order details including order status and payment method |
| Order Items | Product-level order information |
| Products | Product catalog information |

---

# ⭐ Business Process

```text
Customers
        │
        ▼
Orders
        │
        ▼
Order Items
        ▲
        │
Products
```

A dedicated **Calendar Table** is created to support Time Intelligence reporting.

---

# 🏗 Data Model

The project follows a **Star Schema**.

```text
              Customers
                  │
                  │
                  ▼
Calendar → Orders → Order Items ← Products
```

### Relationship Type

- One-to-Many
- Single Direction Filtering

This model improves query performance while following Power BI best practices.

---

# 🚀 Sprint Progress

## ✅ Sprint 1 — Data Import

Completed

### Tasks Completed

- Imported Customers dataset
- Imported Orders dataset
- Imported Order Items dataset
- Imported Products dataset
- Verified column names
- Verified data types
- Loaded datasets into Power BI

---

## ✅ Sprint 2 — Data Cleaning & Transformation

Completed

### Customers

- Removed duplicate records
- Removed empty customer names
- Corrected data types
- Standardized text formatting

### Products

- Removed duplicate records
- Standardized category names
- Verified product information

### Orders

- Removed duplicate records
- Converted Order Date into Date format
- Standardized Status values
- Standardized Payment Method values

### Order Items

- Removed duplicate records
- Verified Quantity values
- Verified Unit Price values
- Created Order Value column

---

## ✅ Sprint 2.4 — Data Modeling

Completed

Implemented:

- Star Schema
- Calendar Table
- Primary & Foreign Key Relationships
- Single Direction Filtering

---

## ✅ Sprint 3 — DAX & Time Intelligence

Completed

### Calendar Table

Created using DAX with:

- Date
- Year
- Quarter
- Month
- Month Number
- Month Year

Marked as the official Date Table.

### Measures Created

#### Revenue

- Total Revenue
- Average Order Value
- Average Revenue per Customer

#### Orders

- Total Orders
- Delivered Orders
- Pending Orders
- Cancelled Orders
- Returned Orders

#### Customers

- Total Customers

#### Products

- Total Products
- Total Quantity Sold

#### KPIs

- Delivery Rate

---

## ✅ Sprint 4 — Dashboard Development

Completed

Designed and developed six fully interactive dashboards using modern dashboard design principles, reusable DAX measures, responsive layouts, and interactive slicers.

---

# 📊 Dashboards

This project consists of **6 fully interactive dashboards**, each designed for a different business function.

---

## 1️⃣ Executive Dashboard ✅

### Purpose

Provides a high-level overview of business performance.

### Includes

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value
- Revenue Trend
- Revenue by Category
- Revenue by City
- Orders by Status
- Interactive Year, Category & City Filters

---

## 2️⃣ Sales Performance Dashboard ✅

### Purpose

Analyze sales performance across products and categories.

### Includes

- Total Revenue
- Total Quantity Sold
- Total Products
- Average Order Value
- Monthly Sales Trend
- Revenue by Category
- Top Products by Revenue
- Orders by Status
- Product & Category Filters

---

## 3️⃣ Customer Insights Dashboard ✅

### Purpose

Understand customer acquisition and purchasing behavior.

### Includes

- Total Customers
- Total Orders
- Average Revenue per Customer
- Total Revenue
- Customer Growth Trend
- Customer Type Distribution
- Revenue by Customer Type
- Customer Distribution by City
- Customer Filters

---

## 4️⃣ Product Analytics Dashboard ✅

### Purpose

Evaluate product performance and inventory status.

### Includes

- Total Products
- Total Quantity Sold
- Total Revenue
- Average Order Value
- Top 10 Products by Revenue
- Revenue by Category
- Product Price Analysis
- Stock Status Distribution
- Product, Category & Stock Filters

---

## 5️⃣ Orders & Delivery Analysis Dashboard ✅

### Purpose

Monitor order fulfillment and operational efficiency.

### Includes

- Total Orders
- Delivered Orders
- Returned Orders
- Delivery Rate
- Orders by Payment Method
- Orders by Status
- Monthly Orders Trend
- Revenue by Payment Method
- Payment Method & Status Filters

---

## 6️⃣ Geographic Insights Dashboard ✅

### Purpose

Analyze business performance across different locations.

### Includes

- Total Revenue
- Total Customers
- Total Orders
- Average Revenue per Customer
- Revenue by City
- Customers by City
- Revenue Trend
- Revenue by Country / Customer Type
- Geographic Filters

---

# 📈 Key Features

- Executive KPI Monitoring
- Six Interactive Dashboards
- Interactive Slicers & Cross Filtering
- Dynamic DAX Measures
- Time Intelligence
- Power Query Transformations
- Star Schema Data Modeling
- Business Performance Analysis
- Customer Analytics
- Product Analytics
- Sales Analytics
- Operations Monitoring
- Geographic Analytics

---

# 📷 Dashboard Preview

Dashboard screenshots will be added after exporting the final report pages.

```text
Images/
│
├── executive_dashboard.png
├── sales_dashboard.png
├── customer_dashboard.png
├── product_dashboard.png
├── orders_dashboard.png
└── geographic_dashboard.png
```

---

# 📚 Skills Demonstrated

## Power BI

- Dashboard Development
- Interactive Reporting
- Cross Filtering
- Drill-down Analysis
- Business Storytelling

## Power Query

- Data Cleaning
- Data Transformation
- Data Validation
- Data Type Management

## Data Modeling

- Star Schema
- Relationships
- Calendar Table
- Measure Table
- Performance Optimization

## DAX

- Measures
- KPIs
- Aggregations
- Time Intelligence
- Business Calculations

## Business Intelligence

- Executive Reporting
- Sales Analytics
- Customer Analytics
- Product Analytics
- Operations Analytics
- Geographic Analytics

---

# 🎯 Learning Outcomes

This project demonstrates practical experience in:

- End-to-End Business Intelligence Development
- Data Preparation using Power Query
- Relational Data Modeling
- Star Schema Design
- DAX Measure Development
- KPI Design
- Dashboard Design Principles
- Interactive Report Development
- Time Intelligence
- Executive Reporting
- Business Storytelling with Data

---

# 🚀 Future Enhancements

- Drill-through Reports
- Custom Tooltips
- Dynamic Report Navigation
- Bookmarks
- Mobile Layout Optimization
- Power BI Service Deployment
- Scheduled Data Refresh
- AI Visuals
- Forecasting
- Row-Level Security (RLS)

---

# 📌 Project Progress

| Sprint | Status |
|----------|--------|
| Sprint 1 – Data Import | ✅ Completed |
| Sprint 2 – Data Cleaning & Transformation | ✅ Completed |
| Sprint 2.4 – Data Modeling | ✅ Completed |
| Sprint 3 – DAX & Time Intelligence | ✅ Completed |
| Sprint 4 – Dashboard Development | ✅ Completed |
| Executive Dashboard | ✅ Completed |
| Sales Performance Dashboard | ✅ Completed |
| Customer Insights Dashboard | ✅ Completed |
| Product Analytics Dashboard | ✅ Completed |
| Orders & Delivery Analysis Dashboard | ✅ Completed |
| Geographic Insights Dashboard | ✅ Completed |

---

# 👨‍💻 Author

**Sai Chetan Reddy**

Computer Science (Artificial Intelligence) Graduate

**GitHub:** https://github.com/saichetanreddy07


---

## ⭐ If you found this project helpful, consider giving it a star!
