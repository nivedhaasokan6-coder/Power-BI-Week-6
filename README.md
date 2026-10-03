# WEEK 5 – POWER BI HEALTHCARE DATA ANALYSIS

## Project Overview

This project focuses on analyzing healthcare data using Microsoft Power BI. The healthcare dataset was cleaned and transformed using Power Query, and separate tables such as **Dim_Patient, Dim_Admission, and Billing** were created. The tables were connected using Patient ID and Admission ID to form a structured data model for analysis.

## Data Preparation

The dataset was imported into Power BI and cleaned using Power Query Editor. Text values were standardized, an **Age Group** column was created, and the required patient, admission, and billing information was organized into separate tables. The Billing table was prepared by merging the required information from the patient and admission dimension tables.

## Data Analysis

DAX measures were created to calculate **Total Patients, Total Billing Amount, Average Billing Amount, Average Length of Stay, and Readmission Rate**. These measures were used to provide important healthcare and billing information for further analysis.

## Dashboard Visualizations

Different Power BI visuals were created to analyze the healthcare data. The dashboard includes **KPI cards, a Matrix, Donut Chart, Stacked Bar Chart, Line Chart, and Clustered Column Chart**. These visuals are used to analyze patient demographics, medical conditions, admission trends, billing amounts, and insurance providers.

## Interactive Filters

Three slicers were added to make the dashboard interactive. The **Insurance Provider, Admission Type, and Date of Admission** slicers allow users to filter the dashboard according to their selected requirements. The connected visuals automatically update based on the selected filters.

## Final Result

The completed Power BI dashboard provides an organized view of healthcare information through interactive visualizations and calculated measures. It allows users to examine patient distribution, billing information, medical conditions, admission trends, and insurance-provider data in a single dashboard.

## Tools Used

* Microsoft Power BI Desktop
* Power Query
* DAX
* Healthcare Dataset
