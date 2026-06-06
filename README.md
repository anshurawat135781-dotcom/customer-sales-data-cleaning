“I worked on a Customer Sales Data Cleaning project where I handled a messy dataset of around 10,000 records using Python.”

🔹 1. Problem Statement

“The dataset was unstructured and had multiple issues like missing values, inconsistent formatting, duplicate records, and outliers, which made it unsuitable for analysis.”

🔹 2. Approach / What You Did

“I followed a structured data cleaning pipeline:”

✅ Data Understanding
Used .info(), .describe(), .isnull() to understand structure and missing data
✅ Handling Missing Values
Used median for numerical columns like Age
Used mode for categorical columns like Gender, City, Country
Used forward fill for date columns
✅ Data Cleaning
Cleaned Age column using regex to extract numeric values
Standardized Gender (male/female) and removed inconsistencies
Converted City & Country to uppercase for consistency
Fixed values like "IND" → "INDIA"
✅ Data Type Conversion
Converted date columns to datetime format
Converted Age to numeric type
✅ Handling Duplicates
Removed duplicate rows
Also handled duplicate Customer_ID by keeping first occurrence
✅ Outlier Treatment
Used Z-score method to detect and remove extreme values
🔹 3. Tools Used
Python
Pandas, NumPy
Matplotlib & Seaborn
🔹 4. Result / Outcome

“After cleaning:”

Dataset reduced from 10,200 to around 9,000 clean records
Data became consistent, accurate, and ready for analysis or machine learning
🔹 5. Key Learning (IMPORTANT ⭐)

“I learned how important data cleaning is because raw data is never perfect. I also improved my skills in handling missing values, standardizing data, and using efficient Pandas techniques.”
