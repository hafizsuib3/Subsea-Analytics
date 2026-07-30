# Subsea Analytics

An end-to-end analytics portfolio project demonstrating how raw subsea business data is sourced, cleaned, stored, modelled, and transformed into interactive Power BI dashboards.

> All company-sensitive names, figures, and operational information shown in this repository have been anonymized or blurred.

## Project Overview

The project combines data from operational records, procurement reports, ERP exports, and manually maintained Excel files.

The data is transformed and standardized before being stored in Microsoft SQL Server. SQL views are then used as reporting sources for Power BI dashboards.

## Data Flow

```text
ERP Exports and Excel Records
             ↓
Data Extraction and Validation
             ↓
Python / Power Query Transformation
             ↓
Microsoft SQL Server
             ↓
Staging Tables and SQL Views
             ↓
Power BI Data Model
             ↓
DAX Measures and KPIs
             ↓
Interactive Dashboards