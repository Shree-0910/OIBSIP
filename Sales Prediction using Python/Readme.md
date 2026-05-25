# 📈 Sales Prediction using Machine Learning

## 📌 Project Overview
This project predicts **sales** based on advertising spends in different media channels such as **TV, Radio, and Newspaper** using Machine Learning models.

The notebook includes:
- Data loading and inspection
- Exploratory Data Analysis (EDA)
- Data preprocessing
- Model training and comparison
- Model evaluation
- Visualization of results

---

# 🎯 Objective
The main objective of this project is to build a machine learning model that can accurately predict product sales based on advertising budgets.

---

# 📂 Dataset Description

The dataset contains **200 rows and 4 columns**.

## Features:
- `TV`
- `Radio`
- `Newspaper`

## 🎯 Target Variable:
- `Sales`

---

# 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 🔍 Project Workflow

## 1️⃣ Data Loading
The dataset was loaded and inspected.

## 2️⃣ Data Cleaning
- Removed unnecessary columns
- Checked for missing values
- Verified data consistency

## 3️⃣ Exploratory Data Analysis (EDA)
Visualizations were created to understand:
- Distribution of variables
- Correlation between features
- Impact of advertising spend on sales

## 4️⃣ Data Preprocessing
The data was prepared for machine learning model training.

## 5️⃣ Model Training
The following models were trained:
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

## 6️⃣ Model Evaluation
Models were evaluated using:
- R² Score
- RMSE
- MAE

---

# 📊 Output Summary

## ✅ Dataset Output

```text
Dataset Shape : (200, 4)
```

---

## ✅ Missing Values Output

```text
TV           0
Radio        0
Newspaper    0
Sales        0

No missing values found.
```

---

## ✅ Train-Test Split Output

```text
Training Samples : 160
Testing Samples  : 40
```

---

# 🎯 Model Comparison Output

```text
==================================================
              MODEL COMPARISON
==================================================

Linear Regression
R² Score : 0.8994
RMSE     : 1.7816
MAE      : 1.4608

--------------------------------------------------

Random Forest Regressor
R² Score : 0.9813
RMSE     : 0.7686
MAE      : 0.6201

--------------------------------------------------

Gradient Boosting Regressor
R² Score : 0.9831
RMSE     : 0.7298
MAE      : 0.6187

==================================================
```

---

# 📈 Cross Validation Output

```text
Cross Validation R² Scores :
[0.9808 0.9866 0.9663 0.9669 0.9871]

Mean CV Score :
0.9775 ± 0.0092
```

---

# 🏆 Final Model Performance

```text
==================================================
         FINAL MODEL PERFORMANCE
==================================================

Best Model : Gradient Boosting Regressor

R² Score : 0.9831
Accuracy : 98.3%

RMSE : 0.7298
MAE  : 0.6187

==================================================
🌟 Excellent Model Performance!
==================================================
```

---

# 📌 Key Insights

- TV advertising has the strongest impact on sales.
- Radio advertising also contributes positively.
- Newspaper advertising has the least impact.
- Gradient Boosting Regressor performed best among all models.

---

# 📁 Project Files

| File Name | Description |
|-----------|-------------|
| `Advertising.csv` | Dataset used for training and testing |
| `Advertising_Sales_Prediction.ipynb` | Complete Jupyter Notebook |



---

# ✅ Conclusion

This project demonstrates how machine learning can be used to predict sales based on advertising spend across multiple media channels.

By applying:
- Data preprocessing
- Exploratory Data Analysis
- Regression techniques
- Model comparison

the project achieved an excellent prediction accuracy of **98.3%** using the **Gradient Boosting Regressor** model.

This project is a strong example of applying **Machine Learning and Data Analytics** techniques to solve a real-world marketing and business problem.

---

# 👤 Author

### Shreyash Gade
