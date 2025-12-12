# Vendor Performance Analysis

This project analyzes vendor performance using purchasing, sales, invoice, and inventory data to identify high and low performing vendors and uncover drivers of profitability and turnover.

## What’s inside

### Notebooks
1.⁠ ⁠⁠ src/01_data_cleaning_and_eda.ipynb ⁠  
   Cleans and explores the datasets, validates joins/keys, and prepares analysis-ready tables.

2.⁠ ⁠⁠ src/02_database_build.ipynb ⁠  
   Builds the consolidated dataset(s) used for vendor-level analysis.

3.⁠ ⁠⁠ src/03_vendor_performance_analysis.ipynb ⁠  
   Performs vendor performance analysis and generates key outputs/insights.

## Data
•⁠  ⁠Raw input datasets are under ⁠ data/raw/ ⁠

•⁠  ⁠Processed / combined datasets are under ⁠ data/processed/ ⁠

•⁠  ⁠Large raw files (if excluded) are documented in ⁠ data/README.md ⁠

## Tools used
Python (pandas, numpy), Jupyter Notebook, and Power BI.

## Outputs
Key outputs include vendor-level performance summaries and insights to support purchasing and inventory decisions.

## Power BI Dashboard

A Power BI dashboard was created to visualize vendor performance metrics and make insights accessible to non-technical stakeholders.

The dashboard highlights:
•⁠  ⁠Vendor-level sales, purchases, and profitability

•⁠  ⁠Inventory movement and turnover patterns

•⁠  ⁠Identification of high- and low-performing vendors

•⁠  ⁠Comparative views to support purchasing and inventory decisions

Due to file size limitations, the Power BI ⁠ .pbix ⁠ file may not be stored directly in this repository. The dashboard was built using the processed datasets generated from the analysis notebooks.
