
# 🏥 End-to-End Healthcare Data Engineering Project with Microsoft Fabric

This project demonstrates a complete real-world data engineering workflow using **Microsoft Fabric**, designed around healthcare analytics. It showcases the use of Fabric’s unified platform to ingest, transform, model, secure, and visualize healthcare datasets efficiently and at scale.

---

## 👩‍💻 Author
**Aneesha Patan Arifulla**  
[LinkedIn](https://www.linkedin.com/in/aneesha-patan/) | [GitHub](https://github.com/Aneesha0112)

---

## 🚀 Project Overview

This end-to-end project leverages Microsoft Fabric’s full stack, using the **Lakehouse architecture** and modern data engineering principles to turn raw healthcare data into secure, insightful, and interactive dashboards.

---

## 🛠️ Tools & Technologies

- Microsoft Fabric
- PySpark (Fabric Notebooks)
- Lakehouse & Delta Tables
- Power BI & Semantic Models
- Pipelines (Data Factory in Fabric)
- GitHub (Data Source)
- Row-Level Security (RLS)

---

## 🔧 Workflow Steps

### 1. **Data Ingestion**
- Pulled hospital data directly from GitHub into the Fabric **Bronze Layer**
- Created an automated pipeline using Fabric’s Copy activity

### 2. **Silver Layer (Processing Zone)**
- Built **dimension tables** (e.g., Patients, Organizations, Payers) using PySpark
- Created **fact tables** (e.g., Encounters, Diagnoses, Medications) as Delta tables
- Ensured clean, enriched, and query-ready schema

### 3. **Gold Layer (Presentation Zone)**
- Created **shortcuts** for dimension tables
- Partitioned **fact tables by month** for performance
- Materialized all tables as **Delta format** in the Gold Lakehouse

### 4. **Semantic Model & Visualization**
- Built a robust Semantic Model using Power BI in Fabric
- Connected Gold Layer tables for unified analytics
- Created dashboards for:
  - Clinical Insights
  - Financial Reports
  - Operational Metrics
  - Patient Engagement

### 5. **Security Layer**
- Implemented **Row-Level Security (RLS)** to restrict data access by user cities
- Applied best practices in data governance and access control

---

## 📈 Key Takeaways

- ✅ Applied **Medallion Architecture** (Bronze ➝ Silver ➝ Gold)
- ✅ Built scalable Delta tables with partitioning
- ✅ Delivered governed analytics via Semantic Model + Power BI
- ✅ Ensured secure data access using RLS
- ✅ Hands-on with end-to-end Fabric services

---

## 📌 Project Highlights

- Real-time pipeline orchestration from GitHub
- Delta Lake optimization using partitioning
- Modular fact/dimension design
- Full Power BI reporting with security
- Practical implementation of healthcare metrics

---

## 🙌 Acknowledgments

Thanks to Microsoft Fabric’s unified analytics platform for enabling this modern data stack experience, and to the healthcare use case for providing a meaningful context to apply it.

----
