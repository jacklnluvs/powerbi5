# Healthcare Data Analysis Dashboard – Power BI

## Project Overview

This project is a **Healthcare Data Analysis Dashboard** developed using **Microsoft Power BI**. The project uses a healthcare dataset and organizes the data into a structured data model for analysis and reporting.

The Power BI data model follows a **star-schema structure** with separate dimension tables and a billing fact table.

## Project Objectives

- Analyze healthcare and patient-related information.
- Organize healthcare data into a structured Power BI data model.
- Analyze billing-related information.
- Create relationships between patient, admission, and billing data.
- Provide a foundation for interactive healthcare reporting and visualization.

## Data Model

The Power BI project contains the following tables:

### 1. healthcare_dataset

This is the main healthcare dataset containing healthcare-related information used for analysis.

### 2. Dim_Patient

The patient dimension table contains patient-related information and supports patient-level analysis.

### 3. Dim_Admission

The admission dimension table contains information related to patient admissions and supports admission-based analysis.

### 4. Fact_Billing

The billing fact table contains billing-related information and is used for analyzing healthcare billing and financial measures.

## Data Model Structure

The project uses a dimensional data-modeling approach:

```text
                    healthcare_dataset
                           |
              +------------+------------+
              |                         |
        Dim_Patient              Dim_Admission
              |                         |
              +------------+------------+
                           |
                      Fact_Billing
```

The model separates descriptive information from transactional billing information, making it easier to perform analysis and build Power BI reports.

##Screenshots:
##Formula:

<img width="1920" height="1080" alt="Screenshot 2026-10-16 134841" src="https://github.com/user-attachments/assets/ead20020-64ab-4142-9462-32c36a571f3a" />

##Model View:

<img width="1920" height="1080" alt="Screenshot 2026-10-16 145216" src="https://github.com/user-attachments/assets/991f5dcc-dd5b-4111-bb0e-a2812b13270f" />

##Table View:
<img width="1920" height="1080" alt="Screenshot 2026-10-16 145235" src="https://github.com/user-attachments/assets/4039f5cb-1fa9-49c2-a26f-9ee9ccf249b0" />



## Tools and Technologies

- **Microsoft Power BI**
- **Power Query** – Data preparation and transformation
- **DAX** – Measures and calculations
- **Power BI Data Modeling** – Relationships and dimensional modeling

## Project File

```text
Task5_Pbi.pbix
```

The `.pbix` file contains the Power BI data model and report configuration.

## Project Structure

```text
Project/
│
├── Task5_Pbi.pbix
└── README.md
```

## Key Areas of Analysis

The dashboard/model can be used to analyze:

- Patient information
- Patient admissions
- Healthcare records
- Billing information
- Patient and admission relationships
- Billing-related trends and summaries

## Data Modeling Approach

The project uses separate dimension and fact tables to organize the healthcare information.

- **Dimension tables** provide descriptive attributes.
- **Fact table** stores measurable billing-related information.
- Relationships between tables allow information from different healthcare areas to be analyzed together.

This approach improves the organization and usability of the dataset for Power BI reporting.

## How to Open the Project

1. Install **Microsoft Power BI Desktop**.
2. Download or clone this project.
3. Open `Task5_Pbi.pbix` using Power BI Desktop.
4. Review the data model and report.
5. Refresh the data if required.
6. Use the available Power BI features to filter and analyze the healthcare data.

## Conclusion

The **Healthcare Data Analysis Dashboard** project demonstrates how Power BI can be used to organize healthcare information into a structured data model. The project contains patient, admission, healthcare, and billing-related tables and uses a dimensional modeling approach to support effective data analysis and reporting.

This project provides a foundation for creating interactive healthcare dashboards and deriving meaningful insights from healthcare and billing data.
