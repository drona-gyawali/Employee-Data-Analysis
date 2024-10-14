![Alt text](https://github.com/drona-gyawali/Employee-Data-Analysis/blob/main/illu_data_cleaning_blog_2-07.jpg)

# Data Cleaning and Analysis Journey


Recently, I embarked on an extensive data cleaning and analysis project revolving around a dataset of employees. This was not just about numbers but ensuring data reliability, usability, and insight generation. Here's an overview of the journey I took:

## Step 1: Handling Missing Values
- I started by identifying columns with missing values.
- For the 'Age' column, I replaced missing values with the median.
- Missing emails were filled with a placeholder: `"missing@example.com"`.

## Step 2: Fixing Data Types
- Converted 'Age' column to integers and 'Join_Date' column to `datetime` format.
- Standardized phone numbers, replacing invalid entries with `NaN`.

## Step 3: Removing Duplicates
- Removed duplicate rows to ensure the data's uniqueness and integrity.

## Step 4: Standardizing Data
- Standardized the 'Gender' column (e.g., normalized 'Male' and 'male') and corrected typos in the 'Department' column (e.g., 'IT', 'it').

## Step 5: Validating Data
- Ensured valid phone numbers and salary ranges within reasonable limits (e.g., between $30,000 and $120,000).

## Step 6: Concatenation
- Split 'Name' column into 'First Name' and 'Last Name' for better organization.

## Step 7: Handling Outliers
- Addressed outliers in 'Salary', capping or removing those beyond realistic thresholds.

## Query-Based Analysis
- Summarized key metrics like average age and salary.
- Conducted department-wise salary analysis and gender-based salary comparisons.
- Investigated top earners and explored hiring trends by date.

## Merging with External Sources
- Merged the cleaned dataset with external employee data, resolving conflicts and enriching the final dataset.

---

This project was a transformative learning experience that helped me refine my data cleaning and analysis skills. I look forward to applying these techniques in future projects to unlock valuable insights.
