# Data Pipeline

## 1. Data Sources

The reporting process begins with data extracted from ERP reports and manually maintained departmental Excel records.

The source data covers areas such as:

- Procurement transactions
- Vendors and procurement categories
- Operational campaigns
- Clients and vessels
- Duration and downtime
- Weather-related delays

## 2. Data Preparation

Source files may contain inconsistent headers, formats, spelling, missing values, and manually entered records.

The preparation process includes:

- Standardizing column names
- Converting data types
- Cleaning dates
- Handling missing values
- Removing invalid records
- Standardizing vendor and vessel names
- Validating records against available source documents

## 3. Data Loading

Prepared data is loaded into Microsoft SQL Server using staging tables.

## 4. SQL Transformation

SQL views are used to:

- Clean and standardize reporting fields
- Exclude invalid records
- Prepare reporting-ready datasets
- Simplify the Power BI connection
- Maintain a consistent reporting layer

## 5. Power BI Data Model

Power BI connects to SQL reporting views.

The semantic model includes:

- Fact tables
- Supporting dimension tables
- Date relationships
- Calendar tables
- DAX measures
- KPI calculations

## 6. Reporting

The final layer consists of interactive Power BI dashboards for procurement and operations monitoring.