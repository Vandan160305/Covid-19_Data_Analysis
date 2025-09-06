# 🦠 COVID-19 Data Analysis

> A concise data analysis project exploring Confirmed, Deaths, and Recovered COVID-19 cases across regions using Python, Pandas, Matplotlib, and Seaborn.



---

## 📌 Project Overview
This project analyzes **COVID-19 data** using **Python, Pandas, Matplotlib, and Seaborn**.  
It focuses on:
- Cleaning and handling missing data  
- Filtering and grouping records  
- Sorting by different criteria  
- Visualizing missing values and trends  

---

## 🔧 Functions & Operations

### Data Handling
- `import pandas as pd` → To import **Pandas** library  
- `pd.read_csv()` → To import the **CSV file** in Jupyter Notebook  
- `df.count()` → Counts the number of **non-null values** in each column  
- `df.isnull().sum()` → Detects **missing values** from the DataFrame  

### Visualization
- `import seaborn as sns` → To import the **Seaborn** library  
- `import matplotlib.pyplot as plt` → To import the **Matplotlib** library  
- `sns.heatmap(df.isnull())` → Displays all columns & missing values in a **heatmap**  
- `plt.show()` → Shows the plot  

### Data Analysis
- `df.groupby('Col_name')` → Groups data by all unique values of the given column  
- `df.sort_values(by=['Col_name'])` → Sorts the entire DataFrame by the given column  
- `df[df['Col_1'] == 'Element1']` → Filtering — Access records with **Element1** only of `Col_1`  

---

## ❓ Problem Statements
1️⃣ Show the number of **Confirmed, Deaths, and Recovered cases** in each Region.  
2️⃣ Remove all the records where **Confirmed cases < 10**.  
3️⃣ Find the Region with the **maximum number of Confirmed cases**.  
4️⃣ Find the Region with the **minimum number of Deaths cases**.  
5️⃣ Report **Confirmed, Deaths, and Recovered cases** in **India till 29 April 2020**.  
6️⃣ Sorting:  
   - **(A)** By **Confirmed cases (ascending)**  
   - **(B)** By **Recovered cases (descending)**  

---

## 🛠️ Tools & Libraries
- **Python 3**  
- **Pandas** → Data manipulation  
- **Matplotlib** → Data visualization  
- **Seaborn** → Heatmap visualization  
- **Jupyter Notebook** → Interactive analysis  

---

## 🚀 Quickstart

```bash
# 1) Clone the repository
git clone https://github.com/your-username/covid19-data-analysis.git

# 2) Install dependencies
pip install pandas matplotlib seaborn

# 3) Launch Jupyter Notebook
jupyter notebook
