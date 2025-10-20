# data-cleaning-netflix-dataset

#Overview
Data cleaning and preprocessing of the Netflix Movies and TV Shows dataset using Excel. Includes handling missing values, removing duplicates, standardizing formats, fixing dates, and renaming columns as part of Elevate Labs Data Analyst Internship Task 1.

## Objective
To identify and fix common data issues such as:
- Missing values  
- Duplicate records  
- Inconsistent text formats  
- Inaccurate date formats  
- Improper column names and data types  '

## Tools Used
- **Microsoft Excel**

## Dataset
**Dataset Name:** Netflix Movies and TV Shows  
**Source:** Kaggle  
**File:** `netflix_titles.csv`

## Steps Performed

1. **Checked for Missing Values:**  
   - Used Excel filters to identify blank cells.  
   - Filled missing values in non-critical columns (like *director* and *cast*) with “Unknown”.  

2. **Removed Duplicate Records:**  
   - Used Excel’s **Remove Duplicates** tool to eliminate duplicate rows.  

3. **Standardized Text Values:**  
   - Converted text columns (like *type*, *country*, and *rating*) to lowercase for consistency.  
   - Used Find & Replace to fix inconsistent spellings.  

4. **Fixed Date Formats:**  
   - Converted `date_added` column to a consistent format (`dd-mm-yyyy`).  

5. **Renamed Columns:**  
   - Made all column headers lowercase and replaced spaces with underscores.  
   - Example: “Show Id” → “show_id”, “Date Added” → “date_added”.  

6. **Checked Data Types:**  
   - Ensured `release_year` is numeric and `date_added` is a date format.
     
7. **Converted it to table:**
   -coverted all data to table so that sorting and filtering will be easier.

9. **Saved Cleaned Data:**  
   - Exported final cleaned dataset as `cleaned_netflix_dataset.xlsx`.

## Results
The cleaned dataset:
- Has **no duplicate records**  
- Contains **consistent formats and values**  
- Is **ready for further analysis and visualization**


