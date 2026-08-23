# 🏗️ Databricks FMCG Data & AI Pipeline

> Enterprise-grade Lakehouse Data Engineering project implementing **Medallion Architecture (Bronze → Silver → Gold)** using Databricks, PySpark, Delta Lake, and SQL for an FMCG retail domain.

---

## 🚀 Project Overview

This project simulates a real-world FMCG enterprise where data arrives daily from multiple companies and operational systems. The pipeline ingests raw transactional data, transforms it into validated business datasets, and delivers analytics-ready tables for reporting and AI use cases.

The entire workflow is designed around the **Bronze, Silver, and Gold** layered architecture commonly used in modern Data Lakehouses.

---

## 🏛️ Lakehouse Architecture

```text
                  FMCG Source Systems
      (Customers • Products • Orders • Pricing)
                         │
                         ▼
                🥉 Bronze Layer (Raw)
          CSV Files • Incremental Loads • Delta
                         │
          Data Validation & Standardization
                         ▼
                🥈 Silver Layer (Clean)
        Dimension Tables + Fact Tables + Quality
                         │
      Business Logic • Joins • Aggregations
                         ▼
                🥇 Gold Layer (Analytics)
      KPI Tables • Dashboards • BI • AI Ready
```

---

## ⚙️ Tech Stack

| Category     | Technologies                   |
| ------------ | ------------------------------ |
| Lakehouse    | Databricks Free Edition        |
| Processing   | PySpark                        |
| Storage      | Delta Lake                     |
| Querying     | SQL                            |
| Domain       | FMCG Retail                    |
| Analytics    | Power BI Ready                 |
| Architecture | Medallion (Bronze/Silver/Gold) |

---

## 📂 Repository Structure

```text
project-de-fmcg-atlikon/
│
├── 0_data/
│   ├── full_load/
│   └── incremental_load/
│
├── 1_codes/
│   ├── setup/
│   ├── dimension_processing/
│   └── fact_processing/
│
├── 2_dashboarding/
│   ├── dashboard.pdf
│   └── SQL Queries
│
└── resources/
    ├── architecture.png
    └── project_diagram
```

---

## 🔄 End-to-End Data Pipeline

### Bronze Layer

* Raw CSV ingestion
* Parent & child company datasets
* Incremental order loading
* Data lineage preservation

### Silver Layer

* Customer cleansing
* Product standardization
* Pricing transformation
* Fact & dimension modeling

### Gold Layer

* Business KPIs
* Sales analytics
* Reporting datasets
* AI & dashboard ready tables

---

## 📊 Business Workflow

1. Ingest raw FMCG datasets
2. Create Delta tables
3. Process dimensions
4. Build fact tables
5. Apply incremental loads
6. Generate analytical datasets
7. Power BI dashboard consumption

---

## 💡 Key Engineering Concepts

* Incremental Data Loading
* Delta Lake Tables
* Medallion Architecture
* Star Schema Preparation
* Dimension & Fact Modeling
* Enterprise Data Lineage
* Analytics-Ready Lakehouse

---

## 📈 Learning Outcomes

* Enterprise Data Engineering workflow
* Databricks notebook development
* PySpark transformation pipeline
* Delta Lake implementation
* Bronze → Silver → Gold architecture
* Real-world FMCG analytics project

---

## 👨‍💻 Author

**Syed Saud Alam**

*Data Engineering • Databricks • PySpark • Lakehouse Architecture*
