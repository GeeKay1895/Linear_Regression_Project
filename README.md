# 📊 Linear Regression Projects

This repository contains two linear regression projects developed using Python and Excel.  
The objective is to perform Exploratory Data Analysis (EDA), build regression models, apply transformations, and select the best model based on performance.

---

# 🚀 Projects Overview

## 1️⃣ Delivery Time Prediction

### 📌 Objective
To predict delivery time based on sorting time and improve model performance using transformations.

### 📂 Dataset
- Sorting Time (Independent Variable)
- Delivery Time (Dependent Variable)

---

### 🔍 Approach

- Performed EDA using scatter plots and correlation analysis
- Built a simple linear regression model
- Evaluated model performance using R² score
- Applied transformations:
  - Log Transformation
  - Exponential Model
- Compared models using R²

---

### 📈 Results

| Model        | R² Score |
|-------------|--------|
| Linear      | 0.68   |
| Log         | 0.695  |
| Exponential | 0.648  |

---

### ✅ Final Model
The **Log Transformation model** was selected as the best model since it provided the highest R² score.

---

### 💡 Business Insight
Delivery time increases with sorting time, but the relationship is slightly non-linear, indicating diminishing returns at higher sorting times.

---

---

## 2️⃣ Salary Prediction

### 📌 Objective
To predict salary based on years of experience and evaluate model performance.

### 📂 Dataset
- YearsExperience (Independent Variable)
- Salary (Dependent Variable)

---

### 🔍 Approach

- Performed EDA using scatter plots and correlation analysis
- Built a linear regression model
- Evaluated performance using R² score
- Tested transformations:
  - Log Model
  - Exponential Model

---

### 📈 Results

| Model        | R² Score |
|-------------|--------|
| Linear      | 0.95   |
| Log         | ~0.93  |
| Exponential | ~0.91  |

---

### ✅ Final Model
The **Linear Regression model** was selected as the best model as it achieved the highest R² score.

---

### 💡 Business Insight
Salary increases consistently with experience, making experience a strong predictor of salary growth.

---

---

# 🧠 Key Learnings

- Importance of EDA before modeling
- Identifying linear vs non-linear relationships
- Using transformations to improve model performance
- Interpreting R² for model evaluation
- Comparing multiple models for best selection

---

# 🛠️ Tools & Technologies

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Scikit-learn
- Microsoft Excel (Regression Analysis)
- Jupyter Notebook

---

# 📂 Repository Structure
Linear_Regression_Projects/

├── Delivery_Time/
│ ├── delivery_time.ipynb
│ ├── delivery_time.html
│ ├── delivery_predictions.csv
│ ├── delivery_time.xlsx
│
├── Salary_Data/
│ ├── salary_model.ipynb
│ ├── salary_model.html
│ ├── salary_predictions.csv
│ ├── salary_model.xlsx
│
├── README.md


---

# 📌 Conclusion

Both projects demonstrate how linear regression can be applied effectively to real-world problems.  
Transformations were useful in improving model performance for non-linear relationships, while simple linear regression performed well for strongly linear data.

---

# 🔗 Author

**Goutham Kumar**

---
