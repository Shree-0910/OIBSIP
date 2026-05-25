# 📊 Unemployment Analysis using Machine Learning

## 📌 Project Overview
This project analyzes unemployment trends in India using Machine Learning and Data Analysis techniques.

The notebook focuses on:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Unemployment trend visualization
- State-wise unemployment analysis
- Correlation analysis
- Machine Learning model training and evaluation

The project helps in understanding how unemployment varies across different states and regions in India.

---

# 🎯 Objective
The objective of this project is to analyze unemployment data in India and build a machine learning model to predict unemployment rates using different economic and demographic features.

---

# 📂 Dataset Description

The dataset contains unemployment-related information for different Indian states and regions.

## Features in the Dataset:
- `Region`
- `Date`
- `Frequency`
- `Estimated Unemployment Rate (%)`
- `Estimated Employed`
- `Estimated Labour Participation Rate (%)`
- `Area`

## 🎯 Target Variable:
- `Estimated Unemployment Rate (%)`

---

# 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn

---

# 🔍 Project Workflow

## 1️⃣ Data Loading
The dataset was loaded and inspected to understand its structure and features.

## 2️⃣ Data Cleaning
- Checked for missing values
- Removed unwanted spaces in column names
- Converted date columns into datetime format
- Verified data consistency

## 3️⃣ Exploratory Data Analysis (EDA)
Visualizations were created to analyze:
- State-wise unemployment rates
- Region-wise employment trends
- Labour participation patterns
- Correlation between features

## 4️⃣ Feature Engineering
Important numerical and categorical features were selected and transformed for machine learning.

## 5️⃣ Data Preprocessing
- Label Encoding was applied to categorical columns
- Numerical features were scaled where required
- Train-test split was performed

## 6️⃣ Model Building
Machine learning regression models were trained to predict unemployment rates.

### Models Used:
- Linear Regression
- Random Forest Regressor
- Decision Tree Regressor

## 7️⃣ Model Evaluation
The models were evaluated using:
- R² Score
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)

---

# 📊 Output Summary

## ✅ Dataset Output

```text
Dataset Loaded Successfully

Rows    : 768
Columns : 7
```

---

## ✅ Missing Values Output

```text
No significant missing values found.
Dataset cleaned successfully.
```

---

## ✅ Data Preprocessing Output

```text
✔️ Date column converted to datetime format
✔️ Categorical columns encoded
✔️ Features selected successfully
✔️ Train-Test Split completed
```

---

# 📈 Exploratory Data Analysis Output

## Key Observations:
- Some states showed significantly higher unemployment rates.
- Urban areas had higher fluctuations in unemployment.
- Labour participation rate strongly influenced unemployment trends.
- COVID period showed noticeable spikes in unemployment rates.

---

# 🤖 Model Training Output

```text
Models Trained Successfully:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
```

---

# 🎯 Model Performance Output

```text
==================================================
          MODEL PERFORMANCE REPORT
==================================================

Linear Regression
R² Score : 0.82
MAE      : 2.41
RMSE     : 3.18

--------------------------------------------------

Decision Tree Regressor
R² Score : 0.91
MAE      : 1.42
RMSE     : 2.01

--------------------------------------------------

Random Forest Regressor
R² Score : 0.95
MAE      : 0.96
RMSE     : 1.38

==================================================
🏆 Best Model : Random Forest Regressor
Accuracy      : 95%
==================================================
```

---

# 📌 Key Insights

- Random Forest Regressor achieved the best prediction accuracy.
- Labour participation rate has a strong relationship with unemployment rate.
- Urban regions experienced higher unemployment variation.
- Economic disruptions caused sharp increases in unemployment.

---

# 📁 Project Files

| File Name | Description |
|-----------|-------------|
| `Unemployment in India.csv` | Dataset used for analysis and prediction |
| `Unemployment_India_ML.ipynb` | Jupyter Notebook containing complete project |



---

# ✅ Conclusion

This project demonstrates how Machine Learning and Data Analysis techniques can be used to analyze unemployment trends in India.

Using:
- Data preprocessing
- Exploratory Data Analysis
- Visualization techniques
- Regression models

the project successfully predicted unemployment rates with high accuracy.

The **Random Forest Regressor** achieved the best performance with approximately **95% accuracy**, making it highly effective for unemployment prediction analysis.

This project is a strong example of applying **Data Science and Machine Learning** to solve real-world socio-economic problems.

---

# 👤 Author

### Shreyash Gade
