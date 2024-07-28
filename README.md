# Credit Card Dashboard Project

## Overview

This project involves the creation of an interactive Credit Card Dashboard using data sourced from Excel, processed through SQL, and visualized in Power BI. The dashboard provides insightful analysis and visual representations of credit card transactions and customer details, offering valuable business insights.

## Project Steps

### 1. Data Preparation

- **Data Source**: The initial dataset was provided in Excel format. This data included detailed information on credit card transactions and customer profiles.
- **Data Cleaning**: The Excel files were cleaned and preprocessed to ensure consistency and accuracy before importing them into a SQL database.

### 2. SQL Database Setup

- **Database Creation**: Two tables were created in MySQL to store the cleaned data:
  - `cc_detail`: Contains credit card transaction details such as annual fees, credit limit, and transaction amounts.
  - `cust_detail`: Includes customer information such as age, income, and education level.
- **Data Import**: Data was imported into the SQL tables using the `LOAD DATA INFILE` command, with attention to ensuring proper data types and formats.

### 3. Data Transformation

- **Data Transformation**: SQL queries were written to clean and prepare the data for analysis. This included handling date formats and ensuring consistency across datasets.
- **Error Handling**: Addressed issues such as incorrect date values and adjusted data formats to ensure successful data loading into the SQL tables.

### 4. Power BI Integration

- **Data Import**: Data was exported from SQL and imported into Power BI for advanced analysis and visualization.
- **DAX Functions**: Utilized DAX (Data Analysis Expressions) to create calculated columns and measures for enhanced data analysis. Examples include calculating average utilization ratios and aggregating transaction amounts.
- **Visualizations**: Developed interactive visualizations and dashboards in Power BI. Key visualizations include:
  - **Transaction Trends**: Line charts displaying transaction amounts over time.
  - **Customer Demographics**: Pie charts and bar graphs showing distribution of customer demographics.
  - **Credit Utilization**: Visualizations highlighting credit utilization ratios and limits.

### 5. Dashboard Features

- **Interactive Filters**: Users can filter data based on various parameters such as card category, time period, and customer demographics.
- **Data Insights**: The dashboard provides actionable insights, including trends in transaction behavior, customer acquisition costs, and delinquency rates.

## Tools and Technologies

- **Excel**: Data cleaning and preprocessing.
- **MySQL**: Data storage and initial processing.
- **Power BI**: Data visualization and dashboard creation.
- **DAX**: Advanced calculations and measures.
