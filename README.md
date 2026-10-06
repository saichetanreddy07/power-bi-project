# 📊 E-Commerce Business Intelligence Dashboard

> An end-to-end Business Intelligence project built using **Microsoft Power BI** to transform raw e-commerce data into actionable business insights through interactive dashboards, data modeling, Power Query, and DAX.

![Status](https://img.shields.io/badge/Status-In%20Progress-orange)
![Power BI](https://img.shields.io/badge/Power%20BI-Desktop-F2C811)
![License](https://img.shields.io/badge/License-MIT-blue)

---

# 📖 Project Overview

Businesses generate massive amounts of transactional data every day, but raw data alone cannot support strategic decision-making.

This project demonstrates the complete Business Intelligence lifecycle by transforming raw e-commerce data into six interactive dashboards that help stakeholders analyze business performance, customer behavior, product sales, operational efficiency, and overall business health.

The project follows industry-standard BI practices including:

- Data Cleaning
- Data Transformation
- Data Modeling
- Star Schema Design
- DAX Measures
- Time Intelligence
- Interactive Dashboard Design
- Business KPI Development

---

# 🎯 Project Objectives

- Build a scalable Business Intelligence solution using Power BI.
- Design a proper Star Schema for efficient reporting.
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

```
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

A dedicated **Calendar Table** is created for Time Intelligence and reporting.

---

# 🏗 Data Model

The project follows a **Star Schema**.

```
              Customers
                  │
                  │
                  ▼
Calendar → Orders → Order Items ← Products
```

Relationship Type

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

Created relationships between all tables.

Implemented:

- Star Schema
- Calendar Table relationship
- Single Direction filtering
- Proper primary and foreign key mapping

---

## ✅ Sprint 3 — DAX & Time Intelligence

Completed

### Calendar Table

Created using DAX.

Includes

- Date
- Year
- Quarter
- Month
- Month Number
- Month Year

Marked as Date Table.

---

### Measures Created

#### Revenue

- Total Revenue
- Average Order Value

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

## ✅ Sprint 4 — Executive Dashboard

Completed

Developed the Executive Dashboard featuring:

### KPI Cards

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value

### Visualizations

- Revenue Trend
- Revenue by Category
- Revenue by City
- Orders by Status

### Interactive Filters

- Year
- Category
- City

### Dashboard Features

- Modern executive layout
- Interactive filtering
- Responsive visuals
- Consistent theme
- Rounded KPI cards
- Business KPI monitoring

---

# 📊 Dashboards

This project will contain **6 fully interactive dashboards**.

---

## 1️⃣ Executive Dashboard ✅

Purpose

Provides a high-level overview of business performance.

Includes

- Revenue KPIs
- Orders KPIs
- Customer KPIs
- Average Order Value
- Revenue Trend
- Revenue by Category
- Revenue by City
- Order Status Analysis

Status

✅ Completed

---

## 2️⃣ Sales Dashboard 🚧

Purpose

Analyze sales performance across products and time.

Planned Visuals

- Monthly Sales
- Sales Trend
- Revenue by Product
- Revenue by Category
- Top Products
- Bottom Products
- Sales by City
- Sales by Payment Method

Status

🚧 Planned

---

## 3️⃣ Customer Dashboard 🚧

Purpose

Understand customer behavior.

Planned Visuals

- Customer Growth
- New vs Returning Customers
- Customer Distribution
- Customer Segmentation
- Top Customers
- Customer Lifetime Analysis

Status

🚧 Planned

---

## 4️⃣ Product Dashboard 🚧

Purpose

Analyze product performance.

Planned Visuals

- Product Performance
- Category Performance
- Quantity Sold
- Inventory Analysis
- Top Products
- Low Performing Products

Status

🚧 Planned

---

## 5️⃣ Operations Dashboard 🚧

Purpose

Monitor order fulfillment and operational efficiency.

Planned Visuals

- Order Status
- Delivery Rate
- Cancelled Orders
- Returned Orders
- Processing Trends
- Fulfillment KPIs

Status

🚧 Planned

---

## 6️⃣ Business Insights Dashboard 🚧

Purpose

Provide overall business insights and executive recommendations.

Planned Visuals

- Business KPIs
- Revenue Growth
- Customer Insights
- Product Insights
- Forecasting
- Key Business Recommendations

Status

🚧 Planned

---

# 📈 Key Features

- Executive KPI Monitoring
- Interactive Filtering
- Time Intelligence
- Dynamic DAX Measures
- Star Schema Data Model
- Power Query Transformations
- Business Performance Analysis
- Customer Insights
- Product Analysis
- Operations Monitoring
- Executive Reporting

---

# 📷 Dashboard Preview

Dashboard screenshots will be added after each dashboard is completed.

```
Images/
│
├── executive_dashboard.png
├── sales_dashboard.png
├── customer_dashboard.png
├── product_dashboard.png
├── operations_dashboard.png
└── business_insights_dashboard.png
```

---

# 📁 Project Structure

```
ecommerce-powerbi-dashboard/
│
├── Dashboard/
│   └── Ecommerce_BI_Dashboard.pbix
│
├── Dataset/
│   ├── customers.csv
│   ├── orders.csv
│   ├── order_items.csv
│   └── products.csv
│
├── Images/
│
├── README.md
│
├── LICENSE
│
└── .gitignore
```

---

# 📚 Skills Demonstrated

### Power BI

- Dashboard Development
- Interactive Reporting
- Drill-down Analysis
- Data Visualization

### Power Query

- Data Cleaning
- Data Transformation
- Data Validation

### Data Modeling

- Star Schema
- Relationships
- Calendar Table
- Data Optimization

### DAX

- Measures
- KPIs
- Aggregations
- Time Intelligence

### Business Intelligence

- Executive Reporting
- Sales Analytics
- Customer Analytics
- Product Analytics
- Operations Analytics

---

# 🎯 Learning Outcomes

This project demonstrates practical knowledge of:

- Business Intelligence
- Data Analytics
- Dashboard Design
- Data Modeling
- Power Query
- DAX
- Time Intelligence
- KPI Development
- Executive Reporting
- Business Storytelling

---

# 🚀 Future Enhancements

- Drill-through Reports
- Custom Tooltips
- Bookmarks & Navigation
- Mobile Layout Optimization
- Forecasting
- AI Visuals
- Row-Level Security (RLS)
- Power BI Service Deployment

---

# 📌 Current Progress

| Sprint | Status |
|----------|--------|
| Sprint 1 | ✅ Completed |
| Sprint 2 | ✅ Completed |
| Sprint 2.4 | ✅ Completed |
| Sprint 3 | ✅ Completed |
| Sprint 4 - Executive Dashboard | ✅ Completed |
| Sales Dashboard | 🚧 Planned |
| Customer Dashboard | 🚧 Planned |
| Product Dashboard | 🚧 Planned |
| Operations Dashboard | 🚧 Planned |
| Business Insights Dashboard | 🚧 Planned |

---

# 👨‍💻 Author

**Sai Chetan Reddy**

Computer Science (Artificial Intelligence) Graduate

GitHub: https://github.com/saichetanreddy07

LinkedIn: *Add your LinkedIn profile here*

---

## ⭐ If you found this project interesting, consider giving it a star!
