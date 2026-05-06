💳 Credit Card Financial Analysis Dashboard

A complete Business Intelligence & Financial Analytics Project built using Power BI, PostgreSQL, and a live database connection to analyze credit card transactions and customer behavior in real time.

This project provides deep insights into:

Revenue trends
Customer spending behavior
Card category performance
Transaction methods
Customer demographics
Weekly financial analysis
📌 Project Overview

The objective of this project is to transform raw credit card transaction data into an interactive and visually rich dashboard for business decision-making.

The dashboard helps stakeholders:

Track financial performance
Analyze customer segments
Identify high revenue sources
Monitor transaction patterns
Compare quarterly growth
Understand customer demographics

🚀 Features
📊 Transaction Dashboard
Total Revenue Analysis
Total Transaction Amount
Interest Earned
Transaction Count
Revenue by Card Category
Revenue by Expenditure Type
Revenue by Chip Usage
Quarterly Revenue & Transaction Trends
Gender-based Revenue Analysis

👥 Customer Dashboard
Revenue by Week
Revenue by Education Level
Revenue by Job Type
Revenue by Age Group
Revenue by Marital Status
Revenue by Income Group
Top Performing States
Customer Income Analysis

🛠️ Tools & Technologies Used
Tool	Purpose
Power BI	Data Visualization & Dashboard Creation
PostgreSQL	Database Management System
SQL	Data Querying & Data Import
CSV Dataset	Source Data
DAX (Data Analysis Expressions)	Calculated Measures & KPIs
Power Query	Data Cleaning & Transformation

🗄️ Database Setup
PostgreSQL Database

A live PostgreSQL database was used to store and manage:

Credit card transaction data
Customer details
Revenue metrics

SQL Import Example
COPY cc_detail
FROM 'C:/cc_add.csv'
DELIMITER ','
CSV HEADER;

📈 KPIs Used
Total Revenue
Total Interest Earned
Total Transaction Amount
Transaction Count
Activation Rate
Delinquent Rate
Quarterly Revenue Growth
Revenue Contribution by Gender
Revenue by Card Category

📊 Dashboard Insights
Transaction Insights
Blue & Silver cards contribute the highest revenue
Swipe transactions dominate customer spending
Q4 recorded the highest transaction count
Revenue increased significantly during the final quarter
Customer Insights
Graduate customers generate maximum revenue
Businessmen and White-collar customers contribute most revenue
Married customers spend more compared to other groups
High income group customers generate the largest revenue share

🔄 Live Database Connectivity

This project uses a live connection between PostgreSQL and Power BI.

Workflow:
Store data in PostgreSQL
Connect PostgreSQL with Power BI
Import tables into Power BI
Create relationships
Build DAX measures
Design interactive dashboards
Auto-refresh data from database

📂 Project Structure
Credit-Card-Financial-Analysis/
│
├── Dataset/
│   ├── cc_detail.csv
│   └── customer.csv
│
├── SQL/
│   ├── database_setup.sql
│   └── queries.sql
│
├── PowerBI/
│   └── Credit_Card_Report.pbix
│
├── Screenshots/
│   ├── transaction_dashboard.png
│   └── customer_dashboard.png
│
└── README.md
📸 Dashboard Screenshots

Transaction Dashboard
Revenue Analysis
Card Usage Trends
Quarterly Performance
Customer Dashboard
Customer Segmentation
Weekly Revenue Trends
Income & Education Analysis

📚 Skills Demonstrated
Data Visualization
Business Intelligence
SQL Query Writing
Data Modeling
Dashboard Design
Data Cleaning
DAX Calculations
PostgreSQL Integration
KPI Analysis
🎯 Business Use Cases

This dashboard can help:

Banks
Financial Institutions
Credit Card Companies
Analysts
Business Teams

to monitor customer activity and financial performance efficiently.

🔮 Future Improvements
Real-time streaming dashboard
Predictive analytics using Python
Fraud detection integration
Advanced drill-through reports
Mobile optimized dashboard
Cloud database integration

👨‍💻 Author

Shubhankar Nautiyal

Snapshot of this project:
