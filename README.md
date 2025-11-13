# ElevateLabs_Task1

🧹 Task 1 — Data Cleaning and Preprocessing

Project: Elevate Labs Internship
Dataset: Customer Support Analysis (from Kaggle)
Tool Used: Python (Jupyter Notebook, pandas library)

📊 Overview

This task focuses on performing data cleaning and preprocessing on a real-world dataset. The goal is to ensure that the dataset is ready for further analysis or modeling by handling missing values, correcting data types, and standardizing column names.

📁 Dataset Details

Dataset Name: Customer Support Analysis

Source: Kaggle

Rows: 2240

Columns: 29

The dataset contains customer-related details such as demographics, spending patterns, and engagement data.

⚙️ Steps Performed

Data Loading

Imported the dataset into Jupyter Notebook using the pandas library.

Loaded the data file using pd.read_csv() with proper delimiter handling.

Exploratory Data Analysis (EDA)

Performed basic exploration using functions like df.info(), df.describe(), and df.head() to understand data structure.

Handling Missing Values

Checked for missing values using df.isnull().sum().

Found that only the Income column had missing values.

Imputed missing values in the Income column using the mean of that column.

Handling Duplicates

Checked for duplicate rows using df.duplicated().sum().

No duplicate records were found in the dataset.

Data Type Correction

Verified each column’s data type using df.dtypes.

Identified that the Dt_Customer column (which represents dates) was of object type.

Converted it into datetime format using pd.to_datetime().

Column Name Standardization

Cleaned and standardized column names by:

Removing unnecessary spaces and special characters.

Converting all names to lowercase for uniformity.

Ensuring readability and proper syntax for analysis.

🧠 Key Learnings

Gained hands-on experience in identifying and handling missing values.

Learned how to validate data types and perform type conversions.

Understood the importance of consistent and clean column naming conventions.

Strengthened skills in pandas-based data cleaning workflows.

🛠️ Technologies Used

Python

pandas

Jupyter Notebook
