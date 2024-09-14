# Python-BookStoreSales-DataCleaning-Project-Pandas

# Project Overview

This project focuses on cleaning and preprocessing bookstore sales data using Python and Pandas. The dataset contained various inconsistencies such as null values, duplicates, and text formatting issues. Additionally, advanced data cleaning tasks, such as formatting phone numbers using regular expressions (regex) and splitting location data into city, state, and street address, were performed to ensure data quality and consistency.

# Steps Involved

# 1. Data Cleaning
Loading Data: Imported the dataset using Pandas.
Handling Missing Values:
Identified columns with null values.
Imputed missing values using appropriate methods (e.g., mean, median, mode) or removed rows/columns with excessive null values.
Removing Duplicates: Detected and removed duplicate entries to ensure data uniqueness.

# 2. Advanced Data Cleaning
Phone Number Formatting:
Used regular expressions (regex) to identify and format phone numbers into a consistent format (e.g., 456-789-8767).
Ensured all phone numbers adhered to the specified format, handling various input formats and correcting errors.

Splitting Location Data:
Split the location data into separate columns for city, state, and street address.
Used string manipulation techniques to accurately extract and assign the correct parts of the address to each column.

# 3. Data Type Adjustments
Converting Data Types: Converted data types to appropriate formats for better performance and compatibility (e.g., converting date strings to datetime objects).

# 4. Additional Cleaning
Removing Irrelevant Columns: Dropped columns that were not useful for analysis.
Outlier Detection and Handling: Identified and handled outliers to ensure data accuracy.

# Tools and Technologies
Python: The primary programming language used for the project.
Pandas: For data manipulation and cleaning.
Regex: For advanced text formatting and validation.

# Conclusion
This project successfully cleaned and preprocessed the bookstore sales data, ensuring high data quality and consistency. The cleaned dataset is now ready for further analysis and can be used to derive meaningful insights about bookstore sales.

