# Projects
a messy 10,000-row sales dataset (dirty_cafe_sales.csv) with missing values, inconsistent entries, and date errors.
dataset loaded into cleaning file (CleaningFile)
The file first searches for missing values('NaN')
Invalid entries ('ERROR'/'UNKNOWN') replaced with 'NaN'
Inconsistent `Total Spent` recalculated from `Quantity × Price`
Missing dates are placed into a seperate file to test statistics
For missing dates, generated synthetic random dates
the cleaned dataset is then saved into 'dirty_cafe_sales-cleaned.csv'
The new dataset is loaded into 'Visualizationfile'
the new file produces insights from the data such as :
1. Item sales by month
2. Revenue by month
3. Revenue from each item
4. Sales distribution by item
