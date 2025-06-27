# Data-Analytics---TASKS1
✅ Data Cleaning Summary Report
1. Removed Missing Values:

Rows with missing values were identified using .isnull().

These rows were either removed or handled appropriately to avoid analysis bias.

2. Removed Duplicate Records:

Duplicate rows were detected using .duplicated() and removed using .drop_duplicates() to ensure data uniqueness.

3. Standardized Column Names:

Column headers were converted to lowercase.

Spaces were replaced with underscores for consistency and compatibility (e.g., Dt Customer → dt_customer).

4. Fixed Inconsistent Data Formats:

The dt_customer column was converted to a consistent format: dd-mm-yyyy using pd.to_datetime().

5. Cleaned Text Values:

Text fields like education, marital_status, etc., were stripped of leading/trailing spaces.

All values were made lowercase to ensure uniform categories.

6. Ensured Correct Data Types:

Columns such as income, kidhome, and teenhome were checked and cast to appropriate numeric types.

Dates were ensured to be in proper datetime format.
