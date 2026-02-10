📊 **Task-1: Data Immersion & Wrangling — Sales Transactions Dataset**

This repository contains Task-1 of my Data Analytics Internship at ApexPlanet Software Pvt Ltd.
The objective of this task was to perform data access, familiarization, data-quality assessment, cleaning, and transformation on a retail sales transactions dataset using Power BI and Power Query.

The project demonstrates a structured, end-to-end workflow that converts raw business data into a validated, analysis-ready dataset, supported by full documentation and reproducible transformation steps.

🎯 **Project Objectives**

The primary goals of this task were to:

Understand dataset structure and business meaning

Create a formal data dictionary

Identify and log data-quality issues

Clean and standardize transactional records

Engineer analytical features

Validate the final output for downstream analytics

🛠 **Tools & Technologies**

Power BI Desktop

Power Query

**GitHub**

📁 Repository Structure
📦 sales-data-wrangling-task1
│
├── 01_raw_sales.csv
├── 02_data_profiling.pbix
├── 03_data_dictionary.pbix
├── 04_data_cleaning.pbix
├── 05_final_dataset.pbix
│
└── README.md


👉 Open the files in numerical order using Power BI Desktop to follow the full workflow.

📄**Dataset Description**

The dataset contains retail sales transactions where:

Each row represents a single customer order

The data includes revenue, profit, quantity, product hierarchy, payment methods, and geographical attributes

Date fields allow time-series and trend analysis

**Original Columns**

Order ID, Amount, Profit, Quantity, Category, Sub-Category, PaymentMode, Order Date, CustomerName, State, City, Year-Month

🔍 Data Profiling & Quality Assessment

Initial exploration was performed in Power BI to evaluate:

Row counts and schema

Data types and completeness

Distribution of numeric measures

Frequency of categorical fields

Date coverage and anomalies

Key Issues Identified

Duplicate Order IDs

Missing values in Amount and Profit

Inconsistent PaymentMode and Category naming

Irregular date formats

Extreme outliers in revenue and profit

Trailing spaces and casing inconsistencies

All issues and resolutions are documented within 02_data_profiling.pbix.

🧹 **Data Cleaning & Transformation (Power Query)**

All cleaning operations were implemented using Power Query in Power BI.

Major transformations included:

Removing duplicate records

Standardizing categorical values

Parsing and converting date columns

Cleaning text fields using trim and case rules

Handling missing values through business logic

Validating numeric ranges for Quantity and Profit

Normalizing the Year-Month field

Each step is visible in the Applied Steps panel inside 04_data_cleaning.pbix.

🛠 **Feature Engineering**

To support downstream analysis, several derived fields were created:

Profit Margin %

Order Month

Order Year

High-Value Order Indicator

These features enhance trend analysis, profitability evaluation, and segmentation.
