--------------------------------------------------------------------------------
## Data Warehouse Project 🏠

## 📋 Overview 

Welcome to the **Data Warehouse and Analytics Project** repository!
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project highlights industry best practices in data engineering and analytics.

---

## 🏗️ The Data Ecosystem
The analytics are built upon a structured environment that integrates data from two primary sources:
- **ERP (Enterprise Resource Planning)**: Sales and operational data.
- **CRM (Customer Relationship Management)**: Detailed customer profiles and interaction history.

Before analysis, the data undergoes a rigorous **Data Quality** process to cleanse and resolve inconsistencies, ensuring that every insight is based on a single, reliable "source of truth".

---

## Objective
Develop SQL and T-SQL based best practices to create a structured, organized, and well-documented Data Warehouse, to consolidate
sales data, enabling analytical reporting, and informed decision-making. It follows the Medalion Architecture, with:
- **Bronze Medalion**
- **Silver Medalion**
- **Gold Medalion**

---

## 🛠️ Technologies & Skills
- **Languages**: SQL, T-SQL (Transact-SQL)
- **Database Engine**: Microsoft SQL Server
- **Data Modeling**: Fact & Dimension Tables (Star Schema)
- **Tooling**: SQL Server Management Studio (SSMS)

---

## Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytical teams.

---

## 📂 Project Structure
```
├── datasets/            # Source data from ERP and CRM systems in CSV format [1], [2]
├── docs/                # Technical documentation and Data Architecture Diagram [1], [3]
├── scripts/             # SQL scripts for ETL processes and analytical queries [1], [2], [4]
│   └── proc_load_silver.sql # Example
├── LICENSE              # MIT License information [1], [4]
└── README.md            # Main project documentation and specifications 
```

---

## License

This project is licensed under MIT License. You are free to use, modify, and share this project with proper attribution.
