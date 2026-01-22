# Data-Analyst-Internship-Task-5

# Task 5 – Python Basics: Reading and Cleaning Data using Pandas

## About the Task
In this task, I worked on basic data reading and cleaning using Python and the Pandas library. The main goal was to understand how Python can be used instead of Excel to clean datasets efficiently and prepare them for analysis.

---

## Dataset
- Titanic Dataset (`tested.csv`)

This dataset contains passenger details such as age, gender, ticket class, fare, and survival status.

---

## Tools Used
- Google Colab
- Python
- Pandas
- NumPy

---

## What I Did in This Task
- Loaded the Titanic dataset using pandas `read_csv()`.
- Viewed the first few rows to understand the data.
- Used `info()` and `isnull().sum()` to check datatypes and missing values.
- Filled missing values in numeric columns like Age and Fare using the median.
- Filled missing values in the Embarked column using the most frequent value (mode).
- Removed the Cabin column because it had too many missing values.
- Checked for duplicate rows and removed them.
- Converted the Survived column to the correct datatype.
- Created a new column called `Age_Group` by grouping passengers based on age.
- Saved the final cleaned dataset as `cleaned_data.csv`.

---

## Outcome
By completing this task, I learned how to clean real-world datasets using Pandas and understood why Python is more efficient than Excel when working with larger datasets.
