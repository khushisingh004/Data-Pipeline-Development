# Data-Pipeline-Development
*Company* : CODTECH IT SOLUTIONS
*Name* : Khushi
*Intern ID* : CT06DG2245
*Domain* : Data Science
*Duration* : 8 WEEKS
*Mentor* : Vaishali
##Description of the TASK##
📝 Project Overview
This repository contains the initial work on a basic ETL (Extract, Transform, Load) pipeline using a sample dataset titled Books.csv. The goal of the project is to explore how raw data can be loaded, cleaned, and prepared for future use in data analysis or machine learning workflows.

This project was created as part of an internship or academic exercise to demonstrate a foundational understanding of working with real-world data using Python, Pandas, and Scikit-learn.

🎯 Objectives
The main purpose of this ETL pipeline is to:

✅ Extract data from a .csv file using Pandas

✅ Begin transforming data: remove duplicates and handle missing values

✅ Prepare for category encoding and feature engineering

⏳ (Upcoming) Save the cleaned dataset to a new CSV file for downstream use

📦 Dataset Information
The dataset Books.csv includes records about various books, potentially including:

Title

Author

Category/Genre

Other metadata (e.g., price, ratings — depending on availability)

The dataset was loaded using pandas.read_csv() with appropriate handling for Windows file paths.


⚙️ Technologies Used
Python – Scripting and logic

Pandas – Data loading and transformation

Scikit-learn – For encoding (planned)

Jupyter Notebook – Interactive code development

🧪 Process Implemented So Far
✅ 1. Extract
The dataset was loaded from a local .csv file using Pandas. The file path was carefully handled using raw string formatting to avoid syntax errors common in Windows environments.

✅ 2. Transform (Partial)
The following cleaning steps were applied:

Duplicate removal using df.drop_duplicates()

Missing value handling with df.fillna("Unknown")

Column formatting by converting all column names to lowercase

Preparation for encoding (encoding is planned in future stages)

📌 Learning Outcomes
Gained hands-on experience in working with CSV files in Python

Learned to handle missing data and duplicates

Practiced standardizing column names and preparing for feature encoding

Understood the structure of a real-world ETL pipeline

*Output of the file* : ![Image](https://github.com/user-attachments/assets/01c5448c-2674-4423-a237-fa8e1501253b)

                      ![Image](https://github.com/user-attachments/assets/fdcba1d3-90e4-4620-83ad-271219eecaac)

