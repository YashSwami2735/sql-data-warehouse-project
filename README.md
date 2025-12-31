# 📊 Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---

## 📘 Project Overview

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse using **Medallion Architecture** — Bronze, Silver, and Gold layers.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.

🎯 This repository is an excellent resource for professionals and students looking to showcase expertise in:

- SQL Development  
- Data Architect  
- Data Engineering  
- ETL Pipeline Developer  
- Data Modeling  
- Data Analytics  

---

## 🛠️ Important Links & Tools

Everything is for **Free!**

- **Datasets**: Access to the project dataset (CSV files)
- **SQL Server Express**: Lightweight server for hosting your SQL database
- **SQL Server Management Studio (SSMS)**: GUI for managing and interacting with databases
- **Git Repository**: Set up a GitHub account and repository to manage, version, and collaborate on your code efficiently
- **DrawIO**: Design data architecture, models, flows, and diagrams
- **Notion**: All-in-one tool for project management and organization
- **Notion Project Steps**: Access to all project phases and tasks

---

## 🚀 Project Requirements

### 🏗️ Building the Data Warehouse (Data Engineering)

#### 🎯 Objective

Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### 📋 Specifications

- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries
- **Scope**: Focus on the latest dataset only; historization of data is not required
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams

---

### 📈 BI: Analytics & Reporting (Data Analytics)

#### 🎯 Objective

Develop SQL-based analytics to deliver detailed insights into:

- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

For more details, refer to **docs/requirements.md**.

---

## 🏛️ Data Architecture

The data architecture for this project follows **Medallion Architecture** with **Bronze**, **Silver**, and **Gold** layers:

### 🔹 Sources
- CRM  
- ERP  
- **Object Type**: CSV Files  
- **Interface**: Files in Folders  

---

### 🥉 Bronze Layer
- Stores raw data as-is from the source systems  
- **Object Type**: Tables  
- **Load**:
  - Batch Processing
  - Full Load
  - Truncate & Insert  
- **Transformations**: None  
- **Data Model**: None (as-is)

---

### 🥈 Silver Layer
- Cleaned and standardized data  
- **Object Type**: Tables  
- **Load**:
  - Batch Processing
  - Full Load
  - Truncate & Insert  
- **Transformations**:
  - Data Cleansing
  - Data Standardization
  - Data Normalization
  - Derived Columns
  - Data Enrichment  
- **Data Model**: None (as-is)

---

### 🥇 Gold Layer
- Business-ready data  
- **Object Type**: Views  
- **Load**: No Load  
- **Transformations**:
  - Data Integrations
  - Aggregations
  - Business Logic  
- **Data Model**:
  - Star Schema
  - Flat Table
  - Aggregated Table  

---

### 📊 Consume
- BI & Reporting  
- Ad-hoc SQL Queries  
- Machine Learning  

---

## 📁 Repository Structure















]
