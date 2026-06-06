🚀 Customer Sales Data Cleaning Project
📌 Overview

This project focuses on cleaning and preprocessing a real-world messy customer sales dataset using Python. The dataset contained over 10,000 records with multiple issues like missing values, inconsistent formats, duplicates, and outliers.

The goal was to transform raw, unstructured data into a clean, reliable, and analysis-ready dataset.

🧠 Problem Statement

Real-world data is often messy and unreliable. This dataset had:

Missing values across multiple columns
Inconsistent formats (e.g., male, M, FEMALE)
Duplicate records and IDs
Incorrect and noisy values (e.g., "51 years", -10, 250)
⚙️ Tech Stack
🐍 Python
📊 Pandas, NumPy
📈 Matplotlib, Seaborn
🔍 Regex (for text cleaning)
🔧 Data Cleaning Steps
✅ 1. Data Understanding
Used .info(), .describe(), .isnull() to analyze structure and missing data
✅ 2. Handling Missing Values
Median → Age (numerical)
Mode → Gender, City, Country (categorical)
Forward Fill → Date columns
✅ 3. Data Standardization
Cleaned Gender → male, female
Standardized City → uppercase & trimmed
Fixed Country → IND, india → INDIA
✅ 4. Feature Cleaning
Extracted numeric values from Age column using Regex
Converted:
Age → numeric
Dates → datetime format
✅ 5. Handling Duplicates
Removed duplicate rows
Removed duplicate Customer_IDs (kept first occurrence)
Reduced dataset from 10,200 → ~9,000 records
✅ 6. Outlier Detection
Used Z-score method to detect and remove extreme values
Visualized using boxplots
📊 Final Outcome

✔ Clean and structured dataset
✔ No missing values
✔ Consistent formatting across all columns
✔ Ready for analysis / machine learning

📁 Project Structure
customer-sales-data-cleaning/
│── data_cleaning.ipynb
│── messy_data.csv
│── cleaned_data.csv
│── README.md
📸 Before vs After (Optional - Add Screenshot)

👉 Add dataset screenshots here to impress recruiters

🚀 Key Learnings
Real-world data is always messy
Data cleaning is the most important step in data analysis
Learned handling:
Missing values
Inconsistent data
Outliers
Data transformation
💼 Why This Project Matters

This project demonstrates strong skills in:

Data preprocessing
Data wrangling
Problem-solving using Python
🔗 Connect With Me
LinkedIn: (Add your link here)
GitHub: (Your profile link)
⭐ If you like this project

Give it a ⭐ on GitHub!

🔥 Pro Tips (Very Important)

To make this even more attractive:

Add dataset screenshots
Add before vs after comparison
Upload notebook with clean comments
Pin this repo on your GitHub
