# Retail Sales Data Cleaning and Analysis

**Prepared by:** Okewu Jeremiah
**Project Type:** Data Science / Exploratory Data Analysis (EDA)
**Tools:** Python, Pandas, Matplotlib, Google Colab, Excel

## Project Overview

This project demonstrates a data analysis workflow using a synthetic Nigerian retail and e-commerce transaction dataset. The work covers data inspection, quality checks, date conversion, sales analysis, grouping, summary reporting, and exporting results into reusable files.

The project was developed as a portfolio exercise to demonstrate practical beginner-level data science skills.

> **Data transparency:** The dataset contains synthetic records. The results are for learning and demonstration purposes and should not be interpreted as verified sales figures for real companies, stores, or Nigerian cities.

## Project Objectives

- Inspect the dataset structure and data types.
- Check for missing values and duplicate records.
- Validate transaction dates, sales amounts, and item counts.
- Analyze sales by month, store label, city label, and payment method.
- Calculate transaction counts, total sales, and average transaction values.
- Export the cleaned data and analysis summaries for further use.

## Tools and Technologies

- **Python:** Data analysis and calculations.
- **Pandas:** Data cleaning, transformation, grouping, and aggregation.
- **Matplotlib:** Charts and visualizations.
- **Google Colab:** Cloud-based Python notebook environment.
- **Microsoft Excel:** Reviewing and presenting tabular results.
- **ReportLab:** Generating the PDF report.

## Dataset

The project uses a 50,000-row sample from the Hugging Face dataset:

[ N i g e r i a n Retail and E-commerce Point of Sale Records](https://huggingface.co/datasets/AhmadBabajoytk/nigerian_retail_and_ecommerce_point_of_sale_records)

The records cover January 1 through October 27, 2024. The data is synthetic and does not establish actual business performance.

## Data Cleaning and Quality Checks

The workflow included:

1. Inspecting the rows, columns, and data types.
2. Checking for missing values and exact duplicate rows.
3. Converting the transaction date column to a datetime format.
4. Checking for invalid dates.
5. Checking for non-positive transaction amounts and item counts.
6. Examining numerical distributions for potential outliers using the interquartile range (IQR) method.
7. Creating a month column for monthly analysis.

The initial checks found no missing values, no exact duplicate rows, no invalid dates after conversion, and no non-positive transaction amounts or item counts in the sample. The IQR checks flagged no outliers in the three numerical columns examined.

These checks do not guarantee that every possible data quality issue has been detected.

## Key Findings

- **Total sample sales:** ₦4,998,963,652.92.
- **Average transaction value:** Approximately ₦99,979.27.
- **Highest monthly total in the sample:** August 2024, approximately ₦531.09 million.
- **Highest store-label total:** Computer Village, approximately ₦514.22 million.
- **Highest city-label total:** Calabar, approximately ₦348.52 million.
- **Most frequent payment method:** Cash, with 25,084 transactions.

**Monthly comparison limitation:** October's records end on October 27, 2024, so October represents a partial month and should not be compared directly with complete months without qualification.

All figures above describe the synthetic sample only.

## Deliverables

- `nigerian_retail_cleaned.csv` — cleaned dataset with the added month column.
- `retail_sales_analysis.xlsx` — Excel workbook containing cleaned data, monthly sales, store performance, city performance, payment summaries, and data quality checks.
- `Okewu_Jeremiah_Retail_Sales_Report.pdf` — formatted PDF summary report.
- The Jupyter Notebook (`.ipynb`) — code and analysis workflow.

## Skills Demonstrated

- Data inspection and quality assessment.
- Handling dates with Pandas.
- Data aggregation using grouping operations.
- Exploratory data analysis.
- Identifying potential outliers with the IQR method.
- Creating charts and summary tables.
- Exporting data to CSV, Excel, and PDF.
- Communicating findings and limitations clearly.

## Conclusion

This project demonstrates an end-to-end introductory data analysis workflow, from inspecting a dataset to producing reusable data files and a report. The next step is to apply the same process to a genuine, appropriately licensed business dataset with a documented source.

## Author

**Okewu Jeremiah**
Aspiring Data Analyst | Python | Pandas | Excel | Data Cleaning and Reporting
