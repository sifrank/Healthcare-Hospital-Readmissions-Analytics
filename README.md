# Healthcare Hospital Readmissions Analytics

**Tools:** SQL Server | T-SQL | Power Query | DAX | Power BI

## Project Overview

This project explores hospital readmission performance using publicly available data from the Centers for Medicare & Medicaid Services (CMS) Hospital Readmissions Reduction Program (HRRP).

The objective is to transform raw healthcare data into a structured, analysis-ready dataset through SQL-based data cleaning, transformation, and validation, establishing the foundation for downstream business intelligence and reporting.

The project demonstrates an end-to-end analytics workflow, incorporating SQL Server data preparation, Power Query transformations, data modeling, and DAX-based analytical measures.

## Data Pipeline

```text
CMS HRRP Raw Data
       ↓
SQL Server Staging
       ↓
SQL Data Cleaning & Transformation
       ↓
Power Query ETL
       ↓
Power BI Data Model
       ↓
DAX Measures
       ↓
Interactive Reporting
```

## SQL Server | Data Preparation & Transformation

Developed a SQL-based data preparation workflow to convert raw CMS healthcare data into a structured reporting dataset.

Key implementations:
- Created raw staging tables to preserve source data.
- Converted raw text fields into appropriate numeric and date data types.
- Handled missing and non-numeric values using `NULLIF()` and `TRY_CONVERT()`.
- Standardized text fields using `LTRIM()` and `RTRIM()`.
- Implemented reporting-period logic to support time-based analysis.
- Maintained separation between raw source data and cleaned reporting tables.

## Power Query | ETL & Standardization

Applied additional transformations to prepare the cleaned dataset for analytical reporting.

- Standardized condition classifications.
- Applied additional data transformations and formatting.
- Validated column data types and reporting consistency.
- Prepared structured data for downstream Power BI modeling.

## Power BI | Data Modeling & Reporting

The SQL and data preparation components establish the foundation for Power BI reporting.

Planned reporting capabilities:
- Executive KPI dashboard
- Hospital-level readmission performance
- Condition-level performance comparisons
- State-level geographic analysis
- Reporting-period trends and comparisons

## Skills Demonstrated

| Area | Skills |
|---|---|
| SQL Development | T-SQL, staging tables, data cleaning, transformations |
| Data Preparation | Data type conversion, NULL handling, standardization, validation |
| ETL | Power Query, data transformation, preparation |
| Business Intelligence | Power BI, data modeling, DAX |
| Healthcare Analytics | Hospital readmissions, quality measures, CMS HRRP data |

## Data Source

Centers for Medicare & Medicaid Services (CMS) — Hospital Readmissions Reduction Program (HRRP).

All analysis is based on publicly available CMS data.
