# Projects
a messy 10,000-row sales dataset (dirty_cafe_sales.csv) with missing values, inconsistent entries, and date errors.
dataset loaded into cleaning file (CleaningFile)
The file first searches for missing values('NaN')
Invalid entries ('ERROR'/'UNKNOWN') replaced with 'NaN'
Inconsistent `Total Spent` recalculated from `Quantity × Price`
Missing dates are placed into a seperate file to see whether if dropped it affects the mean
For missing dates, generated synthetic random dates
