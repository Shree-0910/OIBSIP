# 🚗 Car Price Prediction using Machine Learning

## 📌 Project Overview
This project predicts the **selling price of used cars** based on features such as car age, present price, fuel type, transmission, owner history, and kilometers driven.

The notebook includes:
- Data loading and inspection
- Exploratory Data Analysis (EDA)
- Data preprocessing and feature engineering
- Model training using **Random Forest Regressor**
- Model evaluation and visualization

---

## 🎯 Objective
The main objective of this project is to build a machine learning model that can estimate the price of a used car accurately using historical car data.

---

## 📂 Dataset Description
The dataset contains **301 rows and 9 columns**.

### Features in the dataset:
- `Car_Name`
- `Year`
- `Selling_Price`
- `Present_Price`
- `Driven_kms`
- `Fuel_Type`
- `Selling_type`
- `Transmission`
- `Owner`

### 🎯 Target Variable:
- `Selling_Price`

---

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Project Workflow

### 1️⃣ Data Loading
The dataset was loaded and inspected to understand its structure and data types.

### 2️⃣ Data Cleaning
- Checked for missing values
- Verified column consistency
- Removed unnecessary columns

### 3️⃣ Exploratory Data Analysis (EDA)
Visualizations were created to understand:
- Price distribution
- Correlation between features
- Relationship between selling price and other variables

### 4️⃣ Feature Engineering
A new feature called **Car_Age** was created using:

```python
Car_Age = 2024 - Year
```

After feature engineering:
- `Car_Name` was removed
- `Year` was removed
- Categorical variables were encoded

### 5️⃣ Data Preprocessing
Categorical columns were converted into numerical format to prepare the data for machine learning models.

### 6️⃣ Model Building
A **Random Forest Regressor** was used to train the model.

### 7️⃣ Model Evaluation
The model performance was evaluated using:
- **R² Score**
- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Squared Error)**

---

# 📊 Output Summary

## ✅ Dataset Output

```text
Dataset Shape : (301, 9)

Missing Values :
No missing values found.
```

---

## ✅ Feature Engineering Output

```text
New Feature Created : Car_Age

Dropped Columns :
- Car_Name
- Year
```

---

## ✅ Model Training Output

```text
Model Used :
Random Forest Regressor

Number of Estimators :
100
```

---

# 🎯 Model Performance Output

```text
========================================
       📊 MODEL PERFORMANCE REPORT
========================================

R² Score : 0.9593
Accuracy : 95.9%

MAE      : ₹0.64 Lakhs
RMSE     : ₹0.97 Lakhs

========================================
🌟 Excellent! Model performs very well.
========================================
```

---

# 📈 Sample Prediction Output

| Actual Price (₹ Lakhs) | Predicted Price (₹ Lakhs) | Error |
|-------------------------|----------------------------|-------|
| 0.35 | 0.44 | 0.09 |
| 10.11 | 10.88 | 0.77 |
| 4.95 | 4.91 | -0.04 |
| 0.15 | 0.22 | 0.07 |
| 6.95 | 7.82 | 0.87 |

---

# ✅ Accuracy

The model achieved:

- **R² Score:** `0.9593`
- **Accuracy:** `95.9%`

This indicates that the model predicts used car prices with very high accuracy.

---

# 📌 Key Insights

- **Present_Price** was the most important feature affecting the selling price.
- Older cars generally had lower selling prices.
- Cars with lower kilometers driven tended to have higher resale value.

---

# 📁 Project Files

| File Name | Description |
|-----------|-------------|
| `car data.csv` | Dataset used for training and testing |
| `car_price_prediction.ipynb` | Jupyter Notebook containing complete project |

---



# ✅ Conclusion

This project demonstrates how machine learning can be used to predict used car prices effectively.

Using:
- Data preprocessing
- Feature engineering
- Exploratory Data Analysis
- Random Forest Regressor

the model achieved an accuracy of **95.9%**, making it highly effective for predicting car selling prices.

This project is a strong example of applying **Machine Learning and Data Analysis techniques** to solve a real-world business problem.

---

# 👤 Author

### Shreyash Gade
