# 📊 Enterprise Sales Analytics Platform
### End-to-End Data Warehouse, ETL Pipeline & Business Intelligence Solution

An end-to-end **Business Intelligence (BI)** solution developed as part of our Data Warehousing course. This project transforms raw sales data into meaningful business insights through **ETL pipelines**, a **star-schema data warehouse**, **SSAS multidimensional cube**, and **interactive Power BI dashboards**.

> **Tech Stack:** SQL Server • SSIS • SSAS • Power BI • SQL

---

## Project Overview

Organizations generate large volumes of transactional sales data that are difficult to analyze directly. This project demonstrates how to design a complete BI solution by building a centralized data warehouse and enabling analytical reporting for business decision-making.

The pipeline extracts sales data from multiple sources, transforms and cleans it using **SQL Server Integration Services (SSIS)**, stores it in a dimensional **Data Warehouse**, builds an **OLAP Cube** using **SQL Server Analysis Services (SSAS)**, and visualizes KPIs through **Power BI** dashboards.

---
 

# 🏗️ System Architecture

```text
               Raw Sales Data
                      │
                      ▼
          SQL Server Staging Database
                      │
              SSIS ETL Packages
      (Extract → Transform → Load)
                      │
                      ▼
            Enterprise Data Warehouse
          (Star Schema Data Model)
                      │
             SSAS Multidimensional Cube
                      │
                      ▼
            Power BI Interactive Reports
```

---

#  Data Warehouse Design

The warehouse follows a **Star Schema** architecture.

### Fact Table

- FactSales

### Dimension Tables

- DimCustomer
- DimProduct
- DimDate
- DimRegion
- DimSalesperson

---

# ETL Workflow

The ETL process consists of:

1. Extracting raw sales data
2. Data cleaning
3. Removing duplicates
4. Handling missing values
5. Data transformation
6. Loading into the dimensional warehouse

Implemented using:

- SQL Server Integration Services (SSIS)

---

# Business Intelligence

Using **SSAS**, we developed an OLAP cube with multiple hierarchies enabling multidimensional business analysis.

### Example Hierarchies

- Year → Quarter → Month
- Country → Region → City
- Category → Product
- Customer Segment
- Salesperson Hierarchy

---
 

#  Project Demo

🎥 **Power BI Dashboard Walkthrough**

➡️ **Watch Demo:**  
 https://www.loom.com/share/557a4cd7e8f9405bb1560572173d2587
---

# 🛠️ Technologies Used

| Category | Technologies |
|-----------|--------------|
| Database | SQL Server |
| ETL | SSIS |
| OLAP | SSAS |
| Visualization | Power BI |
| Language | SQL |

---

# 👩‍💻 Team Members

- **Mahnoor Aslam**
- **Naimah Rehman**
- **Ali Abdullah Ayubi**

---

  
