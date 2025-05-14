# Data Management – Pharmaceutical Sales Analysis

This repository contains the final group project report for the *Data Management* module at the University of Warwick, as part of the MSc Business Analytics programme.

The project focuses on building and managing a simulated relational database for a U.S. pharmaceutical market scenario involving the oncology drug **Alunbrig**, marketed by Takeda. The database is designed to represent real-world structures, including payers, plans, lives covered, and sales data. SQL and Python were used to import, structure, and analyze the data.

---

## Project Objective

- Develop a fully normalized database schema in SQLite
- Populate the schema with realistic synthetic data (CSV inputs)
- Perform structured queries and aggregations to extract insights
- Simulate business use cases: contracted vs non-contracted payer analysis, market share by drug, and formulary restrictions

---

## Included File

- [`Data_Management_Group_Project_Report.pdf`](./Data_Management_Group_Project_Report.pdf)  
  This PDF contains the full report including:
  - Entity-relationship design
  - SQL table creation code
  - Data import scripts
  - Insightful queries and result tables
  - Visual analysis and conclusions

> 📌 The original cover page has been removed for clarity and privacy. The report includes **Appendices A–D**, which contain all SQL and Python code used for database creation, population, and querying.

---

## Technologies Used

- **SQLite** – Database engine
- **Python** (`sqlite3`, `csv`, `pandas`) – For batch import, data manipulation, and querying
- **SQL** – Table creation, joins, CTEs, aggregations
- **Microsoft Excel** – For data formatting and some visualizations

---

## Sample Insights Derived

- Month-over-month sales distribution of Alunbrig and competitors
- Comparison of total units sold by contracted vs non-contracted payers
- Impact of formulary restrictions on drug uptake
- Lives covered by each payer and plan across U.S. states

---

## Data Disclaimer

The dataset used in this project is **synthetic and educational**, created for academic purposes only. No real patient, payer, or proprietary business data is included. The data files themselves are not published, but the logic and structure are fully reproducible based on the included code. 

