# Store-Data-analysis-
Sales and profit analysis of the Kaggle Sample Superstore dataset (9,994 rows), an Excel summary workbook, and a Power BI report.

## Data

`SDA.csv` (Kaggle Sample Superstore). The file has no order date column, so there is no monthly trend. It contains 17 exact duplicate rows; the Power BI model removes them, which gives 9,977 rows.

## Key figures (after removing duplicates)

- Total sales: $2.30M
- Total profit: $286K (margin 12.5%)
- West has the highest profit ($108,328.84); Central has the lowest ($39,653.88)

## How to use
- **Excel:** open `SDA.xlsx`. All totals are formulas on the Data sheet.
- **Power BI:** load the CSV, remove duplicates, add the measures from the DAX file, and apply the theme from View .
