
# 🚗 Cars Data Analysis Project

## 📌 Project Overview

This project focuses on **data cleaning and analysis** of a cars dataset using the **Pandas library in Python**. The main objective is to preprocess the data, handle missing values, and extract meaningful insights through filtering and transformations.


---

## 📂 Dataset

* The dataset was imported using `pd.read_csv()`
* It contains information about different cars including attributes like **Make, Origin, Weight, MPG_City**, etc.

---

## ⚙️ Steps Performed

### 1. Data Loading & Exploration

* Imported dataset using `pd.read_csv()`
* Used `head()` to preview data
* Checked dataset size using `shape`

### 2. Data Cleaning

* Identified missing values using:

  ```python
  df.isnull().sum()
  ```
* Filled null values with column mean using:

  ```python
  fillna()
  ```

### 3. Data Analysis

#### ✔ Value Counts

* Analyzed different car manufacturers using:

  ```python
  value_counts()
  ```

#### ✔ Filtering Data

* Filtered records where Origin is **Asia or Europe** using:

  ```python
  isin()
  ```

#### ✔ Removing Unwanted Data

* Removed cars with **Weight > 4000**

#### ✔ Applying Transformations

* Increased all values of `MPG_City` column by 3 using:

  ```python
  apply()
  ```

---

## 📊 Key Insights

* Identified distribution of car manufacturers (Make)
* Cleaned dataset by handling missing values effectively
* Filtered region-specific data for better analysis
* Removed high-weight outliers for better consistency
* Adjusted fuel efficiency values for analysis

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* Jupyter Notebook
---

## 🚀 How to Clone the Project

Follow these steps to run the project locally:

```bash
# Step 1: Clone the repository
git clone https://github.com/sriumamaheswari-pureti/Cars_Data_Analysis.git

# Step 2: Navigate to the project folder
cd Cars_Data_Analysis

# Step 3: Open in Jupyter Notebook
jupyter notebook
```

---

## 👩‍💻 Author

**P. Sri Uma Maheswari**

---

## ✅ Conclusion

This project demonstrates practical usage of **Pandas for data cleaning, filtering, and transformation**, making raw data ready for further analysis or visualization.

---
