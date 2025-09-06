🦠 COVID-19 Data Analysis Project

📌 Overview

This project demonstrates how to analyze COVID-19 data using Python, Pandas, Matplotlib, and Seaborn.
It covers essential data cleaning, grouping, sorting, filtering, and visualization techniques, along with solving real analytical questions.

🔧 Functions & Operations Used

import pandas as pd → Import Pandas library

pd.read_csv() → Load CSV file into a DataFrame

df.count() → Count non-null values of each column

df.isnull().sum() → Detect missing values in the DataFrame

import seaborn as sns → Import Seaborn library

import matplotlib.pyplot as plt → Import Matplotlib library

sns.heatmap(df.isnull()) → Visualize missing values in a heatmap

plt.show() → Display the plot

df.groupby('Col_name') → Group data by unique values of a column

df.sort_values(by=['Col_name']) → Sort DataFrame by column values

df[df.Col_1 == 'Element1'] → Filter records where Col_1 has a specific value

❓ Problem Statements

Show the number of Confirmed, Deaths, and Recovered cases in each Region.

Remove all the records where the Confirmed Cases < 10.

Find the Region with the maximum number of Confirmed cases.

Find the Region with the minimum number of Deaths cases.

Show the Confirmed, Deaths, and Recovered cases from India till 29 April 2020.

Sorting:

(A) Sort the data by Confirmed cases (ascending order)

(B) Sort the data by Recovered cases (descending order)

📊 Tools & Libraries

Python 3

Pandas → Data manipulation

Matplotlib → Data visualization

Seaborn → Heatmap visualization

Jupyter Notebook → Interactive analysis

🚀 How to Run

Install dependencies:

pip install pandas matplotlib seaborn


Launch Jupyter Notebook:

jupyter notebook


Open the notebook and run the analysis step by step.

✅ Conclusion

This project highlights the process of cleaning, analyzing, and visualizing COVID-19 datasets.
It provides clear answers to real-world analytical questions, while also demonstrating the power of Python data libraries in handling and exploring datasets effectively.
