# W3 D3 – n8n Student ETL Pipeline

## Project Overview

This project demonstrates an ETL pipeline created using n8n.

The workflow reads a raw student-enrollment CSV file, cleans the data, removes duplicate records, filters the required students, and creates a clean CSV output file.

## ETL Process

1. Read the raw CSV file.
2. Extract the CSV records.
3. Remove unwanted spaces.
4. Standardize names, cities, courses, emails, and fee status.
5. Remove duplicate students using Student_ID.
6. Keep only students whose Fee_Paid is "yes" and whose Email is not empty.
7. Convert the final data into CSV format.
8. Save the cleaned CSV file.

## Results

- Raw input records: 53
- Records after removing duplicates: 50
- Final cleaned records: 33

## Files

- `student_enrollment_raw.csv` – Raw input data
- `students_clean.csv` – Cleaned output data
- `W3_D3_Student_ETL_Workflow.json` – Exported n8n workflow

## Tools Used

- n8n
- JavaScript
- CSV
- Visual Studio Code
- GitHub