# RollNo_LA1 — Data Cleaning and Preparation

## Lab Assessment 1
**Data Analysis with Power BI & KNIME (SECSE001)**

This repository contains the screenshot report and final cleaned dataset for the Power BI + KNIME data-preparation assessment.

### Included
- `RollNo_LA1_Report.pdf` — Power BI section first, followed by KNIME.
- `Cleaned_Sales.csv` — final cleaned 9-row × 12-column dataset.

### Required workflow
1. Import `orders.csv` and `customers.xlsx`.
2. Remove duplicate order 1006 and the order with missing UnitPrice.
3. Fill missing Quantity with 1.
4. Fill missing Category and Region with `Unknown`.
5. Standardize Category and Region.
6. Set data types and calculate `Sales = Quantity × UnitPrice`.
7. Perform filter, sort and group on a copy of the cleaned 9-row table.
8. Clean customer data and perform a Left Outer join on CustomerID.
9. Handle unmatched customer C07 as `Not Registered / Unknown / Unknown`.

> The Power BI `.pbix` and KNIME `.knwf` files are application-native files and were not available in the uploaded materials used to build this repository package. Export those files from Power BI Desktop and KNIME before final submission if your instructor requires the native project files.
