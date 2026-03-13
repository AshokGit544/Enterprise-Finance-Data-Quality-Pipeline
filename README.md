# Enterprise Finance Data Quality Pipeline

This project cleans and validates messy finance data.

The main idea is simple: before using finance data for reporting, analytics, or LLM work, the data should be checked and cleaned properly.

This project uses sample finance data like vendors, invoices, cost centers, and GL accounts.  
It finds common data problems and creates clean output files.

## What this project does

- creates raw vendor data
- creates raw invoice data
- adds messy data issues on purpose
- checks missing values
- checks duplicate records
- checks invalid GL accounts
- checks invalid currency values
- checks wrong dates
- checks negative or zero amounts
- creates cleaned vendor data
- creates cleaned invoice data
- creates rejected records
- creates validation failure reports
- creates a final cleaned finance dataset

## Main problems checked

This project looks for issues like:

- missing vendor names
- missing vendor IDs
- missing cost centers
- duplicate invoices
- duplicate vendor records
- invalid GL accounts
- invalid currency codes
- negative amounts
- zero amounts
- bad invoice dates
- bad posting dates
- bad due dates
- invalid date sequence

## Files created

After running the notebook, it creates files like:

- `raw_vendors.csv`
- `raw_invoices.csv`
- `cost_centers.csv`
- `gl_accounts.csv`
- `data_profile_summary.csv`
- `cleaned_vendors.csv`
- `duplicate_vendors.csv`
- `cleaned_invoices.csv`
- `rejected_invoices.csv`
- `duplicate_invoices.csv`
- `validation_failures.csv`
- `finance_cleaned_master_dataset.csv`
- `data_quality_summary.csv`

## Tools used

- Python
- pandas
- NumPy
- matplotlib
- Google Colab / Jupyter Notebook

## What this project shows

This project shows how to:

- profile raw finance data
- clean messy text fields
- standardize values
- validate business rules
- separate valid and rejected records
- create a clean finance dataset for next steps

## Why this project is useful

This project is useful because clean data is important before building dashboards, reports, or LLM applications.

It helps turn messy finance data into trusted data.

## How to run

1. Open the notebook in Google Colab
2. Install the required libraries
3. Run all cells
4. Review the output files
5. Upload the notebook and outputs to GitHub
