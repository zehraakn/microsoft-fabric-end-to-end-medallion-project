# 🚀 End-to-End Data Engineering Project | Microsoft Fabric | Medallion Architecture

This repository showcases a **production-style end-to-end data engineering solution**
built using **Microsoft Fabric** and the **Medallion Architecture (Bronze, Silver, Gold layers)**.

The project covers the complete data lifecycle:
from raw data ingestion and transformation to orchestration, semantic modeling,
and interactive reporting with Power BI.

---

##  Project Architecture

- **Raw → Landing → Lakehouse**
- **Bronze Layer**: Raw ingested data
- **Silver Layer**: Cleaned & transformed data
- **Gold Layer**: Business-ready facts & dimensions
- **Semantic Model** for Power BI reporting

---

##  Technologies Used

- Microsoft Fabric
- Fabric Data Factory (Pipelines)
- Fabric Lakehouse (Delta Tables)
- PySpark (Notebooks)
- Power BI
- Medallion Architecture
- Star Schema (Fact & Dimension Modeling)

---

##  Final Dashboard

<img width="1288" height="721" alt="image" src="https://github.com/user-attachments/assets/14d76133-a96c-41ab-a702-353a92de5535" />


**KPIs included:**
- Total Sales
- Total Quantity
- Total Profit
- Customer Count

**Visuals:**
- Sales by Category
- Sales by Sub-Category
- Interactive slicers (Region, Category, Segment)

---

##  Data Pipeline Flow

1. Raw files ingested into Landing zone
2. Landing → Bronze (Delta tables)
3. Bronze → Silver (data cleaning & enrichment)
4. Silver → Gold (fact & dimension tables)
5. Semantic model created
6. Power BI report built on top of semantic model

---

##  Repository Structure

- data/ → Sample sales data
- notebooks/ → PySpark transformation notebooks
- pipelines/ → Fabric Data Factory pipelines
- semantic-model/ → Relationships & measures
- powerbi/ → Power BI report
- screenshots/ → Project visuals

---

##  Learning Outcomes

- Designing scalable data architectures in Microsoft Fabric
- Implementing Medallion Architecture
- Building production-ready data pipelines
- Data modeling with facts & dimensions
- Serving insights with Power BI Semantic Models

---

##  Reference

This project is inspired by the following tutorial:
https://www.youtube.com/watch?v=j8CPUzGrFxM

The implementation was independently recreated and customized for learning purposes.

---

## 👤 Author

**Zehra Akan**  
Data Analyst / Data Engineer  
