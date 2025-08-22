# Banking Customer Query Analytics Pipeline
End-to-end ETL pipeline using Azure Data Factory and Azure SQL

## 📌 Project Description
This project demonstrates an **end-to-end ETL pipeline** using **Azure Data Factory (ADF)** to load banking customer queries from CSV files into **Azure SQL Database** for analytics.

The pipeline was tested successfully with **8 rows copied** from a sample CSV into SQL.

---

## 🎯 Objective
- Automate loading of banking customer queries from raw CSV files  
- Learn and showcase Azure Data Factory pipeline design  
- Validate data ingestion into Azure SQL Database  
- Document and publish the project for the GitHub portfolio  

---

## 🏗️ Architecture Diagram
![Pipeline Architecture](Diagrams/pipeline_architecture.png)

---

## ⚙️ Tech Stack
- **Azure Data Factory** – ETL pipeline orchestration  
- **Azure Storage Account** – CSV source files  
- **Azure SQL Database** – sink table for customer queries  
- **Integration Runtime** – AutoResolveIntegrationRuntime  

---

## 🔄 Pipeline Workflow
1. **Source**: Customer queries stored in Azure Blob Storage (CSV).  
2. **ADF Pipeline**: Copy Activity moves data from Storage → SQL.  
3. **Sink**: Data stored in `dbo.CustomerQueries` table.  
4. **Execution**: Pipeline triggered manually for testing.  
5. **Monitoring**: Run validated in the ADF Monitor tab.  

---

## 📂 Folder Structure

