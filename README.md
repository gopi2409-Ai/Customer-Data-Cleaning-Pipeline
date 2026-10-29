# Customer Data Cleaning Using Pandas

## About the Project
This project uses Python and Pandas to clean a messy customer dataset by handling missing values, duplicate records, invalid ages, and inconsistent city names.

## Features
- Load customer data from CSV.
- Check missing values and duplicate records.
- Standardize city names.
- Handle invalid ages and missing values.
- Remove duplicate rows.
- Export cleaned data to a new CSV file.
- Generate a simple customer summary.

## Files
- `customers.csv` – Original dataset
- `customer_cleaning.py` – Python cleaning script
- `cleaned_customers.csv` – Cleaned dataset
- `README.md` – Project documentation

## Technologies Used
- Python
- Pandas
- NumPy

## How to Run
1. Install the required libraries:

   ```bash
   pip install pandas numpy
   ```

2. Keep `customers.csv` and `customer_cleaning.py` in the same folder.
3. Run the script:

   ```bash
   python customer_cleaning.py
   ```

4. The cleaned data will be saved as `cleaned_customers.csv`.

## Expected Result
The dataset is cleaned by removing duplicates, handling missing values, correcting invalid ages, and standardizing city names.
