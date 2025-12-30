# Customer Churn & Value Dashboard (Power BI – PL-300 Focused)

## 📌 Project Overview
This project demonstrates end-to-end Power BI data modeling, DAX, and visualization
skills aligned with the **Microsoft PL-300: Power BI Data Analyst** certification.
The dashboard analyzes customer churn behavior and key business drivers using a
semantic model and best-practice Power BI design principles.

## 🎯 PL-300 Objectives Covered
This project maps directly to PL-300 skill areas:

- Prepare data using Power Query
- Design and develop a semantic data model
- Create DAX measures for business metrics
- Build interactive and insightful Power BI reports
- Apply data visualization best practices
- Analyze business performance and trends

## 📊 Dataset
- Source: E-commerce customer churn dataset (CSV)
- Records: ~50,000 customers
- Data domains:
  - Customer demographics
  - Purchase behavior
  - Engagement metrics
  - Churn indicator (binary)

**Target column**
- `Churned`  
  - `1` = Customer churned  
  - `0` = Active customer

## 📐 Key Metrics (DAX Measures)
- Total Customers
- Churned Customers
- Churn Rate (%)
- Average Lifetime Value (LTV)
- Average Order Value
- Average Days Since Last Purchase
- Cart Abandonment Rate
- Discount Usage Rate
- Returns Rate
- Engagement metrics (login frequency, session duration, pages per session)

All metrics are defined as **DAX measures** to ensure consistency across visuals.

## 🧠 Semantic Model Design
- Sorting logic implemented using **calculated columns** (e.g., Signup Quarter Sort)
- Behavioral rate columns retain NULL values to avoid statistical distortion
- Business logic implemented in DAX (semantic layer), not Power Query
- Model designed for:
  - Reusability
  - Consistency
  - Accurate aggregation



## 📊 Dashboard Features
- One-page executive-style layout
- Interactive slicers (Country, City, Gender, Signup Quarter)
- KPI cards for high-level performance tracking
- Churn analysis by:
  - Signup quarter
  - Geography
  - Membership duration
- Scatter plot analyzing engagement vs lifetime value
- Clear visual hierarchy and formatting

## 📷 Dashboard Preview
![Customer Churn Dashboard](screenshots/Dashboard_screenshot)

## 🛠 Tools & Technologies
- Power BI Desktop
- Power Query (M)
- DAX
- GitHub (project documentation and versioning)

## 📁 Repository Structure
customer-churn-powerbi-dashboard/
├── data/
│ └── ecommerce_customer_churn_dataset.csv
├── powerbi/
│ └── Customer_Churn_Dashboard.pbix
├── dax/
│ └── measures.md
├── screenshots/
│ └── dashboard_overview.png
└── docs/
└── business_insights.md

## 🚀 How to Use
1. Clone or download this repository
2. Open the `.pbix` file using **Power BI Desktop**
3. Refresh the data if required
4. Use slicers and visuals to explore churn insights

## 📝 Design & Modeling Notes
- NULL values were intentionally preserved for rate and engagement metrics
- Calculated columns were used only when required for sorting or segmentation
- Measures were preferred over calculated columns for aggregations
- Report designed to follow Microsoft Power BI best practices

## 📘 Certification Relevance
This project reflects real-world tasks expected of a **Power BI Data Analyst**
and aligns with PL-300 exam objectives related to:
- Data modeling
- DAX calculations
- Report design
- Business insight generation

