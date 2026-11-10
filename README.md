# Excel Assignment 2: Data Cleaning and Transformation

This repository contains the solutions and workflow for an advanced data cleaning and transformation assignment performed in Google Sheets / Excel. 

## Key Tasks & Implementation Steps

### 1. Handling Missing Values
* **Price Column:** Checked for missing values and established a strategy (e.g., imputing with median/mean price based on category or removing invalid records).
* **Category Column:** Proposed strategies to handle missing categories effectively (e.g., classification based on product name keywords).

### 2. Correcting Inconsistent Data
* Identified inconsistent text formats in the **Product Name** column and typos in the **Category** column.
* Utilized Find and Replace functions to standardize text formats and correct misspellings.

### 3. Removing Duplicates
* Inspected the dataset for duplicate rows across the entirety of each record and cleaned duplicate entries.

### 4. Splitting and Merging Data
* **Split:** Separated the "Product ID" column into **Manufacturing Date** and **Country Code**, cleaning unnecessary characters.
* **Merge:** Combined "Brand Name" and "Product Name" into a single **Product Brand** column.

### 5. Number & Date Formatting
* Formatted the **Price** column into standard currency format.
* Formatted the **Manufacturing Date** column into the standard `DD-MM-YYYY` format.

### 6. Conditional Formatting
* Applied visual data bars / color scales to the **Price** column.
* Created a custom conditional formatting rule in the **Category** column to highlight cells where the category is `"Electronics"`.
