## Data Scientist Job Offers Analysis

### Summary

This project showcases data cleaning and transformation skills using a dataset sourced from Kaggle, publicly available for everyone's use. The dataset is a CSV file containing job offers for Data Scientist positions from the Glassdoor website.

### Data Analysis Steps

- Standardization of column names. Ensure consistency in column names.
- Removing the Competitor column: Removed due to insufficient data (more than 70% unknown).
- Cleaning company names: unnecessary values in the company name have been removed.
- Salary Column Conversion: Converted salary data to integers.
- Split location columns: Split the location and headquarters columns into cities and states.
- Handling of "None" values: To ensure consistency, certain values have been replaced with "NO INFO".
- Job Description Keyword Search: Search keywords in job descriptions to identify required skills.

### Additional Information

- The project was conducted in JupyterLab environment.
- Used Python and its libraries: Pandas, NumPy, re.
- The dataset provides valuable insight into the data scientist job market, helping both job seekers and recruiters.
