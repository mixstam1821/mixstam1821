<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=00B4D8&width=600&lines=Hi%2C+I'm+Michael+Stamatis+%F0%9F%91%8B;Data+Engineer+%7C+AWS+%7C+PySpark+%7C+SQL;" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/michael-stamatis-85756116a/">
    <img src="https://img.shields.io/badge/LinkedIn-Michael%20Stamatis-0077B5?style=flat&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:mixstam1453@gmail.com">
    <img src="https://img.shields.io/badge/Email-mixstam1453@gmail.com-D14836?style=flat&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://mixstam.netlify.app/">
    <img src="https://img.shields.io/badge/Portfolio-mixstam.netlify.app-3423A6?style=flat&logo=google-chrome&logoColor=white"/>
  </a>
</p>

---

## 👨‍💻 About Me

I'm a **Data Engineer** based in Greece, working remotely at **NIKI Digital Engineering** on automotive data pipelines for **BMW** — processing millions of sensor records daily using AWS and PySpark.

My background combines **production data engineering** with **5 years of scientific research**, where I built ETL pipelines processing 20+ TB of satellite climate data during my PhD at the University of Ioannina.

- 🏢 Currently: Data Engineer @ **NIKI Digital Engineering** (BMW project) — remote
- ☁️ Stack: **AWS Glue · Athena · S3 · PySpark · Python · SQL**
- 🔬 Background: PhD researcher — large-scale satellite data pipelines (ERA5, NASA, EUMETSAT)
- 📍 Location: Greece 

---

## 💼 Experience

### Data Engineer & Test Automation Developer
**NIKI Digital Engineering** · Remote · *Jun 2024 – Present*

**Data Engineering:**
- Build production ETL pipelines for automotive data using **AWS Glue and PySpark**, processing millions of sensor records daily
- Design and maintain data tables for analytics used in production environments
- Develop **SQL transformations** and data quality validation frameworks for time-series vehicle data
- Collaborate with stakeholders to optimize pipeline performance and define data schemas
- **Tech:** Python, PySpark, SQL, AWS (Glue, S3, Athena), Docker, Git

**Test Automation:**
- Develop automated test frameworks for ECU validation using EXAM and Python
- Hardware-in-the-loop (HIL) testing

---

### Scientific PhD Researcher
**University of Ioannina** · Ioannina, Greece · *Oct 2020 – Sep 2025*

- Built **CLARISC** — a cloud database integrating EUMETSAT and NASA satellite datasets, processing **20+ TB** of climate data
- Engineered ETL pipelines for large-scale satellite and reanalysis datasets (ERA5, CERES, MERRA-2) using Python, xarray, Dask, and SQL
- Developed **EarthSense** — an interactive web application to visualize research results
- Performed statistical analysis, data validation, and quality control on multi-dimensional time-series datasets
- Published **4 peer-reviewed papers** in high-impact journals (Atmospheric Research, Climatic Change)
- **Tech:** Python (pandas, xarray, Dask, NumPy, SciPy), SQL, Flask, FastAPI, JavaScript, HPC, Linux, Docker, Git, Fortran

**Key Projects:**
- 🌍 EarthSense — Interactive web app for PhD climate research results
- 🛰️ NATEX — Satellite data viewer built with Python, Satpy, and Bokeh
- 🌐 Aether — Quick netCDF explorer
- 📊 ERMES — ERA5 and CAMS reanalysis data explorer

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-005C84?style=flat&logo=postgresql&logoColor=white) |
| **Big Data** | ![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apache-spark&logoColor=white) ![Dask](https://img.shields.io/badge/Dask-FDA061?style=flat&logoColor=white) |
| **Cloud (AWS)** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white) ![Glue](https://img.shields.io/badge/AWS%20Glue-FF9900?style=flat&logo=amazon-aws&logoColor=white) ![S3](https://img.shields.io/badge/S3-569A31?style=flat&logo=amazon-s3&logoColor=white) ![Athena](https://img.shields.io/badge/Athena-232F3E?style=flat&logo=amazon-aws&logoColor=white) |
| **Data Formats** | ![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat&logoColor=white) ![NetCDF](https://img.shields.io/badge/NetCDF-0078D4?style=flat&logoColor=white) ![JSON](https://img.shields.io/badge/JSON-000000?style=flat&logo=json&logoColor=white) |
| **DevOps** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white) |
| **Currently Learning** | ![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apache-airflow&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white) |

---

## 📂 Featured Projects

### 🔍 [data-quality-checker](https://github.com/mixstam1821/data-quality-checker)
> PySpark tool that automatically profiles and validates any dataset before it enters a pipeline.

- Detects **nulls, duplicates, outliers, schema mismatches**
- Uses **Spark SQL** for column statistics and aggregations
- Outputs a structured **JSON quality report**
- Maps directly to AWS Glue → S3 → Athena production workflows

---

### ⚙️ [etl-pipeline](https://github.com/mixstam1821/etl-pipeline)
> A clean, production-style ETL pipeline: Extract → Transform → Load using PySpark + SQL.

- Cleans messy raw data (nulls, casing, invalid values)
- Enriches with calculated columns and business logic
- **Spark SQL aggregations** for analytics-ready output
- Writes **partitioned Parquet** — same pattern as AWS S3/Athena

---
