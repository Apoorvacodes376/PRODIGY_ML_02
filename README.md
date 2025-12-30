# PRODIGY_ML_02

 House Prices – Advanced Regression Techniques
 Project Overview

This project focuses on predicting house sale prices using advanced regression techniques. The objective is to build robust machine learning models by applying feature engineering, ensemble learning, and proper evaluation metrics aligned with real-world practices.

The project is based on the well-known House Prices – Advanced Regression Techniques dataset and emphasizes improving prediction accuracy through data preprocessing and model optimization.

 Goal

To predict the SalePrice of houses using provided features and evaluate the model using Root Mean Squared Error (RMSE) on log-transformed prices, ensuring equal treatment of expensive and inexpensive houses.

 Dataset Description

The dataset contains detailed information about residential houses, including:

Structural features (area, rooms, floors)

Quality and condition indicators

Location-based and utility-related attributes

The target variable is:

SalePrice – the final sale price of each house

 Tools & Technologies Used

Python

Pandas & NumPy – data manipulation

Matplotlib & Seaborn – visualization

Scikit-learn – model building and evaluation

 Methodology
1 Data Preprocessing

Handled missing values using appropriate imputation strategies

Encoded categorical variables

Applied feature scaling where required

Used log transformation on SalePrice to stabilize variance

2️ Feature Engineering

Selected and transformed relevant features

Reduced skewness in numerical variables

Improved model performance through careful feature handling

3️ Model Building

The following models were implemented and compared:

Random Forest Regressor

Gradient Boosting Regressor

These ensemble models were chosen for their ability to capture non-linear relationships and interactions between features.

 Evaluation Metric

RMSE (Root Mean Squared Error) on log(SalePrice)

This metric ensures:

Fair error comparison across price ranges

Alignment with the official competition evaluation method

 Visualizations

Log(Actual) vs Log(Predicted) scatter plots

Residual analysis plots

Feature importance bar charts

Distribution plots for target variable

These visualizations help assess model accuracy, bias, and interpretability.

 Results & Learnings

Feature engineering significantly improved prediction accuracy

Ensemble models outperformed basic regression approaches

Proper evaluation metrics are crucial for fair model assessment

Visualization plays a key role in understanding model behavior

 Conclusion

This project provided hands-on experience with advanced regression techniques, reinforced the importance of data preprocessing, and improved understanding of ensemble learning methods. It reflects a real-world machine learning workflow from raw data to model evaluation.

 Future Improvements

Hyperparameter tuning using GridSearch or RandomizedSearch

Incorporation of additional engineered features

Model ensembling for further performance gains

 Acknowledgements

Dataset and problem inspired by Kaggle’s House Prices – Advanced Regression Techniques challenge.
