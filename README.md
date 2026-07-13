# Northbrew Supply Chain Intelligence Dashboard

## Overview

Northbrew Supply Chain Intelligence Dashboard is an end-to-end Power BI portfolio project that analyses inventory performance, supplier reliability, stockout risk, and procurement cost exposure using a simulated supply chain dataset.

The project was designed to show how business intelligence can support operational and procurement decisions. Instead of only showing charts, the dashboard focuses on answering practical management questions such as where inventory risk is concentrated, which suppliers need review, and where procurement cost exposure is highest.

---

## Business Problem

Northbrew needs better visibility across its supply chain operations. The business holds a high level of inventory value, but stockout risk still appears in specific product categories. At the same time, supplier performance and procurement cost are affected by delivery delays, defect rates, freight cost, and landed cost.

The main business problem is:

> How can Northbrew monitor inventory, supplier reliability, and procurement cost in one reporting system so management can make better supply chain decisions?

---

## Project Objectives

This project was built to create a management-ready Power BI reporting solution. The main objectives were to develop a clear KPI framework, build a star-schema data model, create dashboard pages for different business users, and translate the findings into practical recommendations.

The dashboard focuses on four key business areas:

1. Executive supply chain performance  
2. Inventory risk and stockout exposure  
3. Supplier reliability and quality performance  
4. Procurement cost and freight burden  

---

## Tools and Skills Used

| Area | Tools / Skills |
|---|---|
| Data visualisation | Power BI |
| Data modelling | Star schema, fact and dimension tables |
| Data transformation | Power Query |
| KPI development | DAX measures |
| Business analysis | Requirement framing, insight generation, recommendations |
| Documentation | Final report, data dictionary, project charter |
| Project support | AI-assisted analysis and dashboard planning |

---

## Dataset

This project uses a simulated supply chain dataset created for portfolio and learning purposes. The dataset includes product, supplier, warehouse, inventory, and purchase order data.

The main tables are:

| Table | Description |
|---|---|
| `dim_date` | Calendar table used for time-based analysis |
| `dim_product` | Product information including category and reorder point |
| `dim_supplier` | Supplier information including supplier country |
| `dim_warehouse` | Warehouse and distribution centre information |
| `fact_inventory_daily` | Daily inventory, demand, receipt, and stockout records |
| `fact_purchase_order` | Purchase order, supplier delivery, defect, freight, and landed cost data |

The dataset is simulated, so the findings should not be treated as real operational advice for an existing company. The purpose of the project is to demonstrate business intelligence, data modelling, dashboard design, and decision-support reporting.

---

## Dashboard Pages

The Power BI report contains four main pages.

### 1. Executive Overview

This page gives management a high-level view of supply chain performance. It includes KPIs such as total landed cost, current inventory value, fill rate, stockout count, and defect rate.

The page helps answer:

> Is the supply chain healthy overall?

### 2. Inventory Intelligence

This page focuses on inventory value, demand, receipts, stockout risk, and reorder exposure. It helps identify which categories need replenishment attention and which categories may require overstock monitoring.

The page helps answer:

> Where is inventory risk concentrated?

### 3. Supplier Performance

This page reviews supplier reliability using delivery delay, defect rate, landed cost, and supplier country. It supports supplier review and procurement decision-making.

The page helps answer:

> Which suppliers should management review?

### 4. Procurement Cost & Action Plan

This page analyses purchase value, freight cost, landed cost, and supplier cost exposure. It links procurement spending with operational risk.

The page helps answer:

> Where is procurement cost exposure coming from?

---

## Key Insights

### Inventory value is high, but stockout risk still exists

The dashboard shows that Northbrew may hold a high level of inventory value overall, but stockout risk is still concentrated in specific categories such as Mobile and Accessories. This suggests the issue is not simply about having more inventory. It is more likely related to replenishment timing, allocation, or category-level planning.

### Networking has high inventory value but lower stockout pressure

Networking appears as one of the largest inventory value categories, but it does not create the same level of stockout pressure as Mobile or Accessories. This means Networking may need overstock monitoring rather than urgent replenishment.

### Mobile and Accessories need stronger replenishment review

Mobile and Accessories are more exposed to stockout risk. These categories should be reviewed for safety stock, reorder points, and demand patterns to reduce the chance of missed sales or service issues.

### Supplier fill rate alone is not enough

Supplier fill rate does not vary significantly across suppliers. Because of this, supplier performance should also be reviewed using delivery delays, defect rates, landed cost, and total purchase exposure.

### Freight cost creates hidden procurement exposure

Some suppliers or supplier countries may look acceptable when only purchase value is considered. However, once freight cost and landed cost are included, the true procurement exposure becomes clearer.

---

## Recommendations

Northbrew should review safety stock settings for Mobile and Accessories because these categories carry higher stockout risk. The business should also monitor Networking inventory to reduce the possibility of holding excess working capital in slower-risk categories.

Supplier review should focus on high-spend suppliers that also show delivery delay or quality issues. Procurement decisions should not only compare purchase price, but also include freight cost, landed cost, defect rate, and delivery reliability.

The business should also investigate freight-heavy supplier routes because freight cost may be creating additional cost pressure that is not visible from purchase value alone.

---

## Project Files

| Folder | Description |
|---|---|
| `data/raw/` | Original simulated dataset files |
| `data/processed/` | Processed or cleaned data files if exported outside Power BI |
| `docs/` | Project documentation, data dictionary, DAX measures, findings, and testing files |
| `reports/` | Final written project report in PDF and Word format |
| `screenshots/` | Dashboard page screenshots |
| `powerbi/` | Power BI file information |

---

## Power BI File

The Power BI file is available upon request.

This public repository includes the project documentation, screenshots, final report, and supporting files to demonstrate the analytical process and dashboard design. The `.pbix` file is not uploaded publicly to protect the original project file.

---

## Limitations

This project uses simulated data, so the insights are designed for portfolio demonstration rather than real business decision-making. The dataset does not represent an actual company’s operations.

The project still provides value because it demonstrates how a business intelligence workflow can be structured from business problem definition to dashboard design, KPI development, insight generation, and management recommendations.

---

## Future Improvements

Future improvements could include demand forecasting, reorder point simulation, supplier scorecard weighting, SQL-based data preparation, and a Power BI Service published version with interactive access.

Another improvement would be to add Python or SQL scripts to show the data preparation process before the data is loaded into Power BI.

---

## Project Summary

This project demonstrates my ability to build an end-to-end business intelligence solution using Power BI. It combines data modelling, DAX measures, dashboard design, business analysis, and written reporting to support supply chain decision-making.

The main value of the project is not only the dashboard design, but the full process of turning operational data into clear business insights and practical recommendations.
