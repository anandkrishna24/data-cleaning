 🚀 Task 1 - Data Cleaning & Preprocessing

This repository contains the complete solution for **Task 1** of the AI & ML Internship, which focuses on cleaning and preparing data for machine learning using the Titanic dataset.

---

## 🎯 Objective

To learn how to clean and preprocess raw data by performing:
- Null value treatment
- Categorical encoding
- Feature scaling
- Outlier removal
- Feature engineering

---

## ✅ Key Steps Performed

### 1. 🔄 Data Exploration
- Checked for null values, data types, and descriptive statistics
- Identified columns with missing data like `Age`, `Embarked`, and `Cabin`

### 2. 🧹 Data Cleaning
- Dropped `Cabin` due to excessive missing values
- Filled `Age` with median, `Embarked` with mode
- Removed duplicate entries

### 3. 🔤 Categorical Encoding
- Standardized `Sex` and `Embarked` columns (lowercased/trimmed)
- Used **One-Hot Encoding** with `drop_first=True` for `Sex` and `Embarked`

### 4. 📊 Feature Scaling
- Applied **StandardScaler** to normalize `Age` and `Fare`

### 5. 📉 Outlier Removal
- Used **IQR method** to detect and remove outliers in `Fare`

### 6. 🧠 Feature Engineering
- Added `FamilySize` = `SibSp + Parch`
- Added `IsAlone` = 1 if `FamilySize == 0`, else 0

### 7. 🧾 Final Adjustments
- Dropped irrelevant columns like `Name`, `Ticket`, and `PassengerId`
- Reset the DataFrame index

---

## 🛠 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn (for scaling)

---

## 📚 What I Learned

- How to explore and clean real-world datasets
- Dealing with null values using statistical methods
- Importance of encoding and scaling in machine learning
- Detecting and removing outliers
- Feature engineering to improve model context
- Preparing a dataset that’s ML-ready

---
# data-cleaning
Data Cleaning and Preprocessing 
