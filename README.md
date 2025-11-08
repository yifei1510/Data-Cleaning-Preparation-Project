## **Data Cleaning & Preparation Project – Excel-Based Data Quality Improvement**


### **Executive Summary**

This project demonstrates how raw, messy business data can be transformed into a consistent, accurate, and analysis-ready dataset.
Using Microsoft Excel advanced features (such as IFERROR, TRIM, Data Validation, and structured tables), this project achieved significant improvements in data quality, consistency, and reporting reliability.
As a result, the cleaned dataset can now be used directly for business analysis, financial reporting, and dashboarding — reducing manual rework time and lowering the risk of misleading insight.


### **Business Problem**

In many organizations, raw data contains duplicated values, inconsistent formatting, hidden spaces, missing values, and typographical errors.
These issues block accurate reporting and slow down analysts.

Goal: create a repeatable cleaning workflow that produces trusted data before analysis begins.

### **Methodology**

Data Formatting

1. Standardized formatting (dates, numbers, currency)

2. Identified & removed duplicate or invalid entries

Used Conditional Formatting and Remove Duplicates to identify and eliminate duplicate records.

<img width="940" height="636" alt="image" src="https://github.com/user-attachments/assets/b86e2cf5-a891-42b1-b81b-b2877f074ee6" />

Applied IFERROR to handle missing or invalid calculations gracefully.

Cleaned text fields using TRIM to remove hidden spaces

Applied TRIM function to remove extra/hidden spaces.

<img width="940" height="428" alt="image" src="https://github.com/user-attachments/assets/f977e7e0-159e-4940-ac05-b8797dea25ae" />


Replaced blank values via bulk update

Filled blank cells using bulk update techniques (e.g., Ctrl+Enter).

Replaced missing entries with placeholders like TBA.

<img width="940" height="495" alt="image" src="https://github.com/user-attachments/assets/0fd3e435-0383-46ea-baf3-29d3b17ad026" />

Implemented Data Validation (dropdown lists) to control user input

Built dropdown lists to prevent incorrect entries.

<img width="940" height="489" alt="image" src="https://github.com/user-attachments/assets/fe4568ce-8da3-45c5-97ed-3874186bea95" />


Converted dataset into Excel Tables for structured data management
<img width="940" height="533" alt="image" src="https://github.com/user-attachments/assets/f72a15c3-b034-4e14-998c-9ad30f81fddf" />


Error-Free Reporting

Cleaned and standardised columns for accurate calculations.

Used Find & Replace for bulk corrections across datasets.

<img width="940" height="355" alt="image" src="https://github.com/user-attachments/assets/66686b5e-b932-4cc9-8849-cc439bd1b5b9" />


### **Tools & Skills Demonstrated**

Excel Advanced Functions: TRIM, IFERROR, conditional formatting

Data Validation & Controlled Input

Duplicate detection & formatting standardization

Spreadsheet data modeling & preparation for reporting

### **Results & Business Recommendations**

Delivered an analysis-ready clean dataset

Reduced risk of wrong reporting due to inconsistent input

Improved trust in downstream insights and decision making

Business Recommendation:
Apply this Excel cleaning template across other business source files to standardize data quality before reporting.
Future versions of this workflow could be automated using Python / Power Query to reduce the manual steps further.

### **Next Steps**

Apply the same pipeline at scale (CSV, database exports)

Migrate the workflow to Python / Pandas or ETL tools

Build dashboards (Power BI / Excel charts) based on the cleaned dataset

Evaluate weak spots or limitations in the original raw data source
