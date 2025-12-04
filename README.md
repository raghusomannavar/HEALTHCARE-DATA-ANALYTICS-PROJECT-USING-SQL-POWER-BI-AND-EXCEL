HEALTHCARE DATA ANALYTICS PROJECT USING SQL AND POWER BI

PROJECT OVERVIEW
This project demonstrates an end-to-end Healthcare Data Analytics workflow using SQL Server and Power BI. The project focuses on analyzing patient, hospital, clinical, and financial data to generate meaningful business insights. The solution covers data cleaning, validation, KPI building, dashboard creation, drill-through analysis, and publishing for portfolio use.

TOOLS AND TECHNOLOGIES USED
SQL Server
SSMS
Power BI Desktop
Microsoft Excel
Git and GitHub

DATASET SOURCE AND CREDIT
The dataset used in this project is sourced from the Kaggle platform. All credit for the original dataset goes to the respective dataset creator on Kaggle. The dataset is used only for learning, educational, and portfolio demonstration purposes.

DESIGN AND DOCUMENTATION SUPPORT
ChatGPT was used only for guidance on KPI identification, dashboard Requirements, and documentation preparation for GitHub. All data analysis and implementation were performed independently.And here ChatGPT worked as a client of this data.

DATASET DESCRIPTION
The dataset contains patient demographic details such as age, gender, and blood type. It includes hospital and doctor information, admission and discharge dates, medical conditions, medications, test results, insurance provider details, billing amount, room numbers, and engineered features such as length of stay, age group, high cost flag, chronic flag, and emergency flag.

PROJECT ARCHITECTURE
Excel to SQL Server to Power BI to GitHub

SQL WORK PERFORMED
Database and table creation
Data import using SSMS Import Wizard
Billing amount cleaning and conversion from text to numeric
Data validation for age, gender, dates, billing, and emergency flags
Duplicate record removal
Data governance using SQL check constraints
Creation of financial, clinical, and operational KPI queries

POWER BI DASHBOARD PAGES
Executive Overview
Clinical Analysis
Financial Analysis
Operational Analysis
Hospital Level Drill-Through
Doctor Level Drill-Through

KEY KPIS
Total patients
Total revenue
Average billing
Average length of stay
Emergency percentage
Chronic patient percentage
Abnormal test result percentage
Revenue by hospital
Revenue by insurance provider
Doctor workload
Room utilization
Monthly admissions trend
Monthly revenue trend

RESULTS AND BUSINESS INSIGHTS
The project identifies top revenue-generating hospitals, high-volume diseases, emergency workload trends, chronic patient cost impact, abnormal test rates, doctor workload imbalance, room utilization patterns, and seasonal admission and revenue trends. These insights support hospital resource planning, financial strategy, clinical quality monitoring, and operational efficiency improvement.

KEY FEATURES
Interactive slicers for hospital, disease, gender, insurance, and admission type
Hospital and doctor-level drill-through analysis
SQL-based data validation and governance
Real-time KPI updates in Power BI

REPOSITORY STRUCTURE
PowerBI Dashboard.pdf
healthcare_dataset_cleaned_csv2.csv
SQL QUERIES FOR PROJECT.pdf
README.md


USE CASE
This project is designed for hospital operations analysis, clinical quality monitoring, financial revenue tracking, healthcare decision support, and executive reporting.

AUTHOR
Raghu -- Data Analyst

DISCLAIMER
This project is created strictly for learning, practice, and portfolio purposes. The dataset is publicly available and does not contain real patient information. No real hospital decisions should be made using this data.
