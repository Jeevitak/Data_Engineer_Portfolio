Welcome! This repo contains real-world data engineering projects demonstrating my skills in data pipelines, cloud tools, SQL, and dashboarding.
## 📊 Airflow Sales Analytics Pipeline

A complete data pipeline built using Apache Airflow and Google Cloud tools.

### 🔧 What it does:
- Detects a sales CSV file in Google Cloud Storage (GCS)
- Loads the data into a BigQuery staging table
- Creates region-wise filtered tables and reporting views in BigQuery
- Final dataset is visualized using Looker Studio

### 🧰 Tech Stack:
- Apache Airflow (developed in PyCharm IDE)
- Google Cloud Composer Sandbox
- Google Cloud Storage (GCS)
- BigQuery
- Looker Studio

📁 **[View Project Folder](./Airflow_Sales_Analytics_Pipeline)**  
🖼️ Includes DAG code, flowchart PDF, and environment setup (`requirements.txt`)

# 🍽️ Swiggy End-to-End Data Pipeline using Snowflake & Streamlit

This project showcases a complete data engineering pipeline built using **Snowflake**, with **slowly changing dimension (SCD)** handling, **incremental loads**, and a **Streamlit dashboard** for Swiggy data insights. A real-world demonstration of building scalable, business-focused analytics solutions.

---

## 🚀 Project Overview

- Designed an end-to-end **ETL pipeline** using Snowflake for ingestion, transformation, and consumption layers.
- Implemented **SCD logic** using `stage`, `clean`, and `consumption` tables to track historical changes in dimensional data.
- Created **initial load** scripts and supported **incremental updates** using date-based logic.
- Developed an interactive **Streamlit dashboard** to analyze Swiggy order trends.
- Created Snowflake **views** for semantic layers and included **lineage diagrams** for architecture clarity.

---

## 🧠 Key Features

- ✅ Initial & Incremental Load support with daily/monthly ingestion simulation
- 🧊 SCD Type-2 tracking using merge logic across layered Snowflake tables
- 📂 Modular SQL scripts for stage → clean → consumption flow
- 📊 Streamlit Dashboard:
  - Filter data by **Month** and **Year**
  - Metrics:  
    - Total Revenue  
    - Number of Orders  
    - Average Revenue per Order  
    - Max Order Value  
    - Average Revenue per Item
  - Top 10 Restaurants by Month
- 🖼️ Included lineage diagrams for views and table architecture

---

## 🖼️ Dashboard Snapshots

| KPI Dashboard | Monthly Trends | Top 10 Restaurants |
|---------------|----------------|--------------------| 
Folder [Swiggy_Pipeline]

---

## 🔧 Tech Stack

| Tool           | Purpose                          |
|----------------|----------------------------------|
| **Snowflake**  | Data warehousing, SCD tracking   |
| **SQL**        | ETL logic, view creation         |
| **Python**     | Streamlit dashboard development  |
| **Streamlit**  | Front-end for data visualization |
| **Git**        | Version control & project hosting|




