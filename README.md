# 🚢 AI & ML Internship Task 1: Data Cleaning & Preprocessing

## 📌 Objective
Clean and preprocess the Titanic dataset for machine learning.

---

## 🛠 Tools Used
- Python (Google Colab)
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (for encoding and scaling)

---

## ✅ Steps Completed

1. **Dataset Loading**
   - Titanic dataset loaded from open source (via GitHub CSV link).

2. **Missing Value Handling**
   - `Age` filled using median.
   - `Embarked` filled using mode.
   - `Cabin` dropped due to excessive null values.

3. **Categorical Encoding**
   - `Sex` encoded using Label Encoding.
   - `Embarked` encoded using One-Hot Encoding.

4. **Feature Scaling**
   - `Age` and `Fare` normalized using Standard Scaler.

5. **Outlier Detection & Removal**
   - Boxplots used for visualization.
   - IQR method used to remove extreme outliers in `Age` and `Fare`.

---

## 🧾 Output
- ✅ Cleaned dataset: `cleaned_titanic.csv`  
- ✅ Final shape: ~823 rows × 11 columns (after outlier removal)

---

## 📁 Files Included
- `cleaned_titanic.csv` – Final cleaned dataset
- `titanic_cleaning.ipynb` – Full code implementation
- `README.md` – This file

---

