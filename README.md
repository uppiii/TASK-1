📄 README.md
📌 Task 1: Data Cleaning and Preprocessing
🎯 Objective

Clean and prepare the raw dataset (marketing_campaign.csv) by handling missing values, duplicates, inconsistent formats, and data types.

🛠 Tools Used

Python (Pandas, NumPy)

Jupyter Notebook

🚀 Steps Performed

Loaded Dataset

Imported raw dataset with pd.read_csv().

Column Cleaning

Converted column names to lowercase and removed extra spaces.

Date Formatting

Converted dt_customer column to datetime.

Ensured consistency in date format.

Duplicate Removal

Identified and removed duplicate records using drop_duplicates().

Kept the latest record when duplicates existed.

Missing Values Check

Used isna().sum() to identify missing values in the dataset.

(⚠️ To-do: Fill or handle missing values appropriately, e.g., with fillna() or imputation).

Data Type Fixes

Converted columns to appropriate data types (e.g., integers, datetime).

Final Dataset

Cleaned dataset ready for further analysis or modeling.

(⚠️ To-do: Export cleaned dataset with to_csv() for submission).

📊 Summary of Changes

Standardized column names.

Converted and standardized date format.

Removed duplicate rows.

Checked and prepared data types.

Verified missing values.
