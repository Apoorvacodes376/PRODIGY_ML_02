# PRODIGY_ML_02


---

#  House Prices – Advanced Regression Techniques

##  Project Overview

This project focuses on predicting house sale prices using advanced regression techniques. The goal is to build accurate and robust machine learning models by applying **feature engineering**, **ensemble learning**, and **proper evaluation metrics** aligned with real-world practices.

The project is based on the **House Prices – Advanced Regression Techniques** dataset and emphasizes improving performance beyond basic linear regression models.

---

##  Objective

* Predict the **SalePrice** of houses using provided features.
* Minimize prediction error using **Root Mean Squared Error (RMSE)** on **log-transformed SalePrice**.
* Apply feature engineering and ensemble models to improve accuracy.

---

##  Dataset Description

The dataset contains information related to residential homes, including:

* Property size and layout
* Quality and condition attributes
* Location and utility-related features

**Target Variable:**

* `SalePrice` – Final sale price of the house.

---

##  Technologies Used

* **Python**
* **Pandas** – Data manipulation
* **NumPy** – Numerical computations
* **Matplotlib & Seaborn** – Data visualization
* **Scikit-learn** – Model building and evaluation

---

##  Methodology

### 1. Data Preprocessing

* Handled missing values using appropriate imputation strategies.
* Converted categorical variables using encoding techniques.
* Applied feature scaling where required.
* Used **log transformation** on `SalePrice` to reduce skewness.

### 2. Feature Engineering

* Selected relevant numerical and categorical features.
* Reduced skewness in numerical variables.
* Improved model learning through feature transformations.

### 3. Model Building

The following models were implemented:

* **Random Forest Regressor**
* **Gradient Boosting Regressor**

These ensemble models were chosen due to their ability to capture complex, non-linear relationships.

---

##  Evaluation Metric

* **Root Mean Squared Error (RMSE)** on **log(SalePrice)**

This metric:

* Treats prediction errors of low- and high-priced houses equally.
* Matches the official evaluation method used in the dataset challenge.

---

##  Visualizations

The following visualizations were used for evaluation and interpretation:

* Log(Actual) vs Log(Predicted) scatter plot
* Residuals vs predicted values plot
* Feature importance bar charts
* Distribution of log-transformed SalePrice

These plots help assess model accuracy, bias, and feature influence.

---

##  Results & Key Learnings

* Feature engineering significantly improves model performance.
* Ensemble models outperform basic regression approaches.
* Log transformation is essential for fair evaluation.
* Visualization is critical for understanding model behavior.

---

##  Conclusion

This project provided hands-on experience with **advanced regression techniques** and demonstrated the importance of preprocessing, feature engineering, and ensemble learning in real-world machine learning problems.

---

##  Future Enhancements

* Hyperparameter tuning using GridSearchCV or RandomizedSearchCV.
* Advanced feature selection techniques.
* Model ensembling for further accuracy improvements.

---

##  Acknowledgements

This project is inspired by the **House Prices – Advanced Regression Techniques** dataset and is part of a structured learning task focused on applied machine learning.

---

