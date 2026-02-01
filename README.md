🚀 14 Days of Databricks – End-to-End Data Engineering & AI Challenge

A hands-on 14-day Databricks challenge focused on building production-grade data engineering, analytics, machine learning, and AI workflows using the Lakehouse architecture on a real-world e-commerce dataset.

This repository demonstrates how raw event data evolves into governed, optimized, analytics-ready, and ML-driven insights, following modern industry practices.

🎯 Challenge Objective

The goal of this challenge was to gain real-world experience with:

- Distributed data processing using Apache Spark
- Lakehouse architecture (Bronze → Silver → Gold)
- Reliable data storage with Delta Lake
- Workflow orchestration and automation
- SQL analytics and dashboards
- Machine learning with experiment tracking
- AI-powered analytics using Databricks tools

By the end of 14 days, the project delivers a full data → analytics → ML → AI pipeline.

📦 Dataset

E-commerce Behavior Data from a Multi-Category Store (Kaggle)
🔗 https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store

The dataset contains large-scale user event data such as:

- product views
- add-to-cart events
- purchases
- timestamps
- user and product identifiers

It is well suited for big data engineering, analytics, and machine learning workflows.

🏗️ Lakehouse & Medallion Architecture

The project is built using the Databricks Medallion Architecture:

- Bronze Layer – Raw, immutable event ingestion
- Silver Layer – Cleaned, validated, and enriched data
- Gold Layer – Business-ready aggregates and analytics tables

📌 Architecture overview

<img src="images/medallion_architecture_bronze_silver_gold.jpg" alt="Medallion Architecture" width="900">

This architecture ensures:

- data quality enforcement
- clear separation of concerns
- scalability and maintainability
- production readiness

🔁 Data Engineering Pipeline (Days 1–7)
Key Capabilities Implemented

- Apache Spark fundamentals and lazy evaluation
- PySpark DataFrame transformations and joins
- Window functions for behavioral metrics
- Delta Lake ACID transactions and schema enforcement
- MERGE-based incremental processing
- Time travel, ZORDER optimization, and VACUUM
- Automated Bronze → Silver → Gold pipelines
- Databricks Jobs with multi-task orchestration
- This phase focuses on reliability, scalability, and automation.

📊 SQL Analytics & Dashboards (Days 8–10)

After building clean Gold tables, the focus shifted to analytics and storytelling:

- Unity Catalog for governance and organization
- SQL Warehouses for analytical workloads
- Complex SQL analytics (CTEs, window functions)
- Interactive dashboards with filters and scheduling
- Performance optimization via partitioning and query plan analysis

📌 Business dashboard example

<img src="images/sql_dashboard.jpg" alt="SQL Dashboard" width="900">

These dashboards convert complex pipelines into clear, actionable insights for stakeholders.

🤖 Machine Learning & MLOps (Days 11–13)

This phase bridges data engineering and data science, focusing on scalable ML workflows.

ML & Statistical Work

- Descriptive statistics and hypothesis testing
- Feature engineering from behavioral event data
- A/B test design and metric comparison
- MLflow experiment tracking and model registry

Models Trained

- Linear Regression
- Decision Tree
- Random Forest

Models were compared based on performance, scalability, and interpretability.

📌 Parallel execution & Spark coordination during model training

<img src="images/spark_parallel_coordination.jpg" alt="Spark Parallel Coordination" width="900">

📌 MLflow run details and experiment comparison

<img src="images/mlflow_run_details.jpg" alt="MLflow Run Details" width="900">

These visuals show:

- how Spark distributes ML workloads
- how multiple models are trained and evaluated consistently
- how MLflow enables reproducible, auditable experimentation

🤖 AI-Powered Analytics (Day 14)

The final day explored next-generation analytics using AI:

- Databricks Genie for natural language → SQL
- Mosaic AI capabilities
- NLP-based sentiment analysis on product reviews
- AI-assisted insight generation

This demonstrates how AI integrates directly into modern data platforms.

📌 Key Outcomes

- Built a production-style Lakehouse data platform
- Implemented ACID-compliant Delta pipelines
- Automated workflows with orchestration
- Delivered SQL dashboards for business users
- Trained and compared ML models with MLflow
- Integrated AI-powered analytics into the pipeline

This project reflects how data engineering, analytics, ML, and AI converge in real-world systems.

🧰 Tech Stack

- Databricks Community Edition
- Apache Spark & PySpark
- Delta Lake
- Unity Catalog
- SQL Warehouses
- MLflow
- Spark ML
- Databricks Genie & Mosaic AI

👨‍💻 Author

Yoseph Negash

📧 yosephn22@gmail.com

📅 2026
