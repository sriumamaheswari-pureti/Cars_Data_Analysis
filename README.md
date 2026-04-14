Here is your **final clean, professional README.md** (ready to copy & upload to GitHub) 👇

---

# 🚗 Cars Data Analysis Project

## 📌 Project Overview

This project focuses on **data cleaning and analysis** of a cars dataset using the **Pandas library in Python**. The objective is to preprocess raw data, handle missing values, and perform analysis to extract meaningful insights.

---

## 📂 Dataset

* Dataset loaded using `pd.read_csv()`
* Contains car attributes such as **Make, Origin, Weight, MPG_City**, etc.

---

## 🧰 Key Commands Used

```python
import pandas as pd - Import library
pd.read_csv() - Load dataset
head() - View first 5 rows
shape - Check rows & columns
df.isnull().sum() - Find missing values
fillna() -  Handle null values
value_counts() - Count unique values
isin() - Filter data
```

---

## ⚙️ Analysis Performed

### 1. Data Cleaning

* Detected missing values using `df.isnull().sum()`
* Filled null values with **mean of respective columns** using `fillna()`

### 2. Value Counts Analysis

* Identified different **car makes**
* Calculated their occurrence using `value_counts()`

### 3. Data Filtering

* Filtered records where **Origin is Asia or Europe** using `isin()`

### 4. Removing Unwanted Records

* Removed rows where **Weight > 4000** to eliminate outliers

### 5. Applying Transformation

* Increased all values in **MPG_City column by 3** using `apply()`

---

## 📊 Key Insights

* Cleaned dataset by handling missing values
* Identified distribution of car manufacturers
* Filtered region-based data (Asia & Europe)
* Removed high-weight outliers for better analysis
* Improved MPG values for analysis

---
## 🛠️ Tools & Technologies

* Python
* Pandas
* Jupyter Notebook
---

## 🚀 How to Run the Project

```bash
# Clone the repository
git clone https://github.com/sriumamaheswari-pureti/Cars_Data_Analysis.git

# Navigate to folder
cd Cars_Data_Analysis

# Open Jupyter Notebook
jupyter notebook
```

---

## 👩‍💻 Author

**P. Sri Uma Maheswari**

---

## ✅ Conclusion

This project demonstrates practical skills in **data cleaning, filtering, and transformation using Pandas**, making raw data ready for analysis and real-world applications.

---

