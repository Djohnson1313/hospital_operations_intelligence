<p align="center">
    <img src="assets/doc_stock.jpg"
         width="1000"
         height="400">
</p>

# Hospital Operations Analysis

This Hospital Operations Analysis is an end to end healthcare analytics case study that transforms raw CSV files into a normalized relational database and uses SQL and Python to evaluate the operational and financial performance of a simulated multi branch hospital network. The project demonstrates database design, data modeling, SQL querying, data visualization, and business analysis by answering executive, branch, operational, and financial business questions. Findings are presented in a structured report that mirrors the workflow of a real world data analyst, from data preparation through actionable business insights.

# Project Overview

Modern healthcare organizations generate large volumes of operational and financial data that can be used to improve efficiency, monitor performance, and support strategic decision making. This project simulates the work of a healthcare data analyst.

The project follows an end to end analytics workflow beginning with database design and data preparation before progressing into business focused analysis. A relational database was built in SQLite using primary and foreign key relationships to model patients, doctors, appointments, treatments, and billing information. SQL was then used to answer business questions across multiple areas of hospital operations, while Python (Pandas and Matplotlib) was used to create visualizations and communicate findings through a structured analytical report.

The analysis is organized into five key business areas :

- Executive Performance evaluates overall organizational performance through key performance indicators such as total revenue, patient volume, appointment volume, average revenue per patient, and monthly revenue trends.
- Branch Performance compares hospital locations by examining revenue, patient volume, appointment activity, doctor workload, and branch level performance metrics.
- Operations Performance investigates operational efficiency through appointment completion rates, cancellations, no shows, scheduling trends, and physician workload.
- Financial Performance examines revenue drivers including treatment profitability, insurance payer mix, billing activity, payment status, and other financial indicators.
- Patient Demographics looks into who the actual patients are, using age / gender distribution, the treatments they are receiving, and patient retention.

Rather than focusing solely on writing SQL queries, the objective of this project is to demonstrate the complete analytical process, from database design and querying to data visualization, interpretation, and communication of business insights. The notebook is structured to resemble a professional analytics report, with each business question supported by SQL, visualizations, and written conclusions.

## Example Business Questions 

- Executive Performance
    - What is total revenue
    - What is the average revenue per patient
- Branch Performance
    - What branch has the highest revenue per patient
    - Which branches are growing or declining over time
- Operations Performance 
    - What months are the busiest
    - Which departments have the highest workload
- Financial performance
    - What is the revenue per treatment 
    - What is the average bill amount per patient
- Patient demographics
    - What is the patient age distribution
    - New vs. returning patients 

# Tech Stack
- SQL
- Python
- Pandas
- Matplotlib
- Jupyter notebook
- Gitbash
- Github

# Key Skills Demonstrated 

- Relational database design
- Entity relationship design
- Database normalization
- SQL joins
- Aggregations
- Subqueries
- Date functions
- Data visualizations
- Business analysis
- Technical documentation

## Project status

This project is actively being expanded.

Current progress includes :

- Relational database design - complete
- Executive performance analysis - complete
- Branch performance - complete 
- Operations performance analysis - complete
- Financial performance analysis - currently in progress
- Patient demographics - planned
- Tableau dashboard - planned

## Repository Structure

```
├── assets
├── .gitignore
├── README.md
└── hospital_operations_analysis.ipynb
```
