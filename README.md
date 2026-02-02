# 🚀 Modern Data Stack (Local) – End-to-End Data Engineering Project

## 📌 Overview

This project demonstrates a **modern data stack running fully locally with Docker**, reproducing a real-world analytics workflow:

> **Ingestion → Warehouse → Transformation → Orchestration → Analytics**

It showcases core data engineering skills:
- ETL pipeline design  
- Data modeling with dbt  
- Workflow orchestration with Airflow  
- Data warehousing in PostgreSQL  
- Analytics & BI dashboards  

All components are containerized and reproducible.

## 🛠 Tech Stack

- **Python** – data ingestion & cleaning  
- **PostgreSQL** – data warehouse  
- **dbt** – transformations & data modeling  
- **Apache Airflow** – orchestration  
- **Docker & Docker Compose** – containerization  
- **Metabase / Power BI / Tableau** – dashboards

```
Sources → Ingestion → Transform → Analytics → Orchestration
   ↓         ↓          ↓          ↓            ↓
Multiple   Python       dbt      PostgreSQL   Airflow
Formats    pandas      SQL       Power BI     Docker
```


