# 📊 CSV Data Explorer

A simple Python project that loads a CSV file and explores key statistics using **pandas**. This script helps in understanding the structure, quality, and summary of the dataset before deeper analysis or modeling.

---

## 🎯 Objective of the Task

The goal of this project is to **explore a CSV file and summarize key stats** to get a quick overview of the dataset. This includes:
- Understanding the column structure and data types
- Identifying missing values
- Summarizing numerical features using basic statistics

---

## 🧰 Tools & Libraries Used

- **Python 3**
- **pandas** – for data loading, exploration, and summary

---

## 🧪 Methodology / Approach

1. **Load the Dataset**:
   - Reads a `.csv` file using `pandas.read_csv()`

2. **Inspect the Data**:
   - Prints column names
   - Displays total number of rows
   - Shows data types of each column

3. **Explore Summary Statistics**:
   - Uses `.describe()` for quick statistical overview (mean, std, min, max, etc.)

4. **Check Missing Values**:
   - Uses `.isnull().sum()` to identify any null entries in the dataset

---

## 📁 Dataset

- You can use any dataset in `.csv` format
- Example files:
  - `iris.csv`
  - `titanic.csv`
  - or your own custom dataset (e.g., `sales_data.csv`)

Ensure the CSV is in the same folder or specify its path in the script.

---

## 💡 Skills Gained

- Working with CSV files in Python
- Exploring data structure and types
- Summarizing numerical features
- Identifying and handling missing data
- Writing clean and reusable EDA scripts

---

## ▶️ How to Run

```bash
pip install pandas
python csv_data_explorer.py
