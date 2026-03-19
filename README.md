Student Alcohol Consumption Dataset README
Dataset Title

Student Alcohol Consumption Dataset

Dataset Description

This dataset contains information about students, including their age, study time, and alcohol consumption levels. It is used to analyze student behavior and understand patterns related to alcohol consumption and academic habits.

The dataset includes both numerical and categorical variables, making it suitable for statistical analysis and data visualization.

Dataset Structure

The dataset contains 300 rows and 5 columns.

Variables

age – Age of the student (Numerical)

studytime – Amount of time spent studying (Numerical / Ordinal scale)

Walc – Weekend alcohol consumption level (Categorical / Ordinal)

Dalc – Weekday alcohol consumption level (Categorical / Ordinal)

absences – Number of school absences (Numerical)

Purpose of the Dataset

This dataset is used for:

Learning data exploration

Performing descriptive statistics

Creating data visualizations

Understanding distribution and patterns in student data

It is commonly used in data science and statistics exercises, especially for univariate analysis.

Source of the Dataset

Kaggle Dataset (Student Alcohol Consumption)
https://www.kaggle.com/datasets

(Insert the exact dataset link if required by your instructor.)

Usage

This dataset can be used with:

Python (Pandas, Seaborn, Matplotlib)

Jupyter Notebook

Data analysis and visualization projects

Example code to load the dataset:

import pandas as pd

df = pd.read_csv("student_alcohol_consumption_300x5.csv")
df.head()
Notes

The dataset is intended for educational and analytical purposes.

Some variables use a scale (for example alcohol consumption levels) rather than exact quantities.
