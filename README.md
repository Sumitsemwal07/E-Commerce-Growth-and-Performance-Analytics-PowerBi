# E-Commerce Growth & Performance Analytics
A Power BI project designed to analyze e-commerce business performance with a focus on growth, customer behavior, and product-level efficiency.
The project follows a real-world analytics approach, starting from raw transactional data and ending with interactive dashboards built for business decision-making rather than exploratory experimentation.

## Project Objective
The primary objective of this project is to provide a clear and structured view of e-commerce performance by answering key business questions such as:

- How is overall revenue and order activity trending?
- How actively are customers engaging with the platform?
- Which products and categories contribute most effectively to growth?
- Is performance driven more by volume or pricing?

The dashboard emphasizes clarity, correctness, and analytical intent over visual novelty.

---

## Dashboard Structure

The report is organized into three analytical views:

**Overview**  
Provides an executive-level snapshot of overall business performance using core KPIs, geographic distribution, and high-level trends.

**Customer Growth**  
Focuses on customer behavior and engagement, including repeat purchasing patterns and order frequency.

**Product Performance**  
Analyzes category and product-level performance, highlighting demand patterns and pricing efficiency through metrics such as Average Selling Price.

Navigation between pages is handled through a fixed navigation panel to maintain a consistent user experience.

---

## Key Metrics

The dashboard is built around business-relevant metrics, including:

- Total Revenue  
- Total Orders  
- Active Customers  
- Total Customers  
- Average Orders per Customer  
- Revenue per Customer  
- Average Selling Price (ASP)  

No profit or cost-based metrics are included, as cost data is not available in the source dataset. Assumptions were intentionally avoided to preserve analytical integrity.

---

## Data & Modeling Approach

- Raw e-commerce data was used in CSV format.
- All data cleaning and transformations were performed within Power Query.
- A star schema data model was implemented:
  - Fact table: Orders
  - Dimension tables: Customers, Products, Calendar
- DAX measures were created for KPIs and analytical calculations.

The model is designed to support flexible slicing and aggregation across time, geography, customers, and products.

---

## Tools Used

- Power BI Desktop  
- Power Query  
- DAX  
- Data Modeling  
- Data Visualization  

---

## Project Assets

- A short dashboard walkthrough video is available in the `Demo` folder.
- Static dashboard previews are available in the `Screenshots` folder.
- Raw datasets are provided in the `Dataset` folder for reference.
- A data model diagram is included in the `Documentation` folder.

---

## Notes

This project is intended to demonstrate analytical thinking, KPI design, and dashboard structuring rather than domain-specific business optimization.  
All data used is representative and intended for demonstration purposes only.
