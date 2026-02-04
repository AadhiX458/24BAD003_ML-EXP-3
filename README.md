# 24BAD003_ML-EXP-3
Linear & Logistic Regression – In-Lab Exercise

Objective

Implement, evaluate, and optimize Linear Regression and Logistic Regression models using real-world datasets. This project focuses on data preprocessing, model training, evaluation metrics, visualization, and optimization techniques.



Scenario 1: Ocean Water Temperature Prediction

Dataset

* CalCOFI Oceanographic Dataset
* Source: Kaggle
* [https://www.kaggle.com/datasets/sohier/calcofi](https://www.kaggle.com/datasets/sohier/calcofi)

Target Variable

* T_degC – Water Temperature (°C)

Input Features

* Depth (m)
* Salinity
* Oxygen
* Latitude
* Longitude

Workflow

* Data loading and cleaning
* Missing value handling (mean/median imputation)
* Feature scaling using StandardScaler
* Train-test split
* Linear Regression model training
* Model evaluation using MSE, RMSE, R² Score
* Visualization of actual vs predicted values and residual errors
* Model optimization using feature selection, Ridge and Lasso regression



Scenario 2: LIC Stock Price Movement Prediction

Dataset

* LIC Stock Price Dataset
* Source: Kaggle
* [https://www.kaggle.com/datasets/debashis74017/lic-stock-price-data](https://www.kaggle.com/datasets/debashis74017/lic-stock-price-data)

Target Variable (Derived)

Price Movement

* 1 → Closing Price > Opening Price
* 0 → Closing Price ≤ Opening Price

Input Features

* Open
* High
* Low
* Volume

 Workflow

* Data loading and preprocessing
* Binary target variable creation
* Missing value handling
* Feature scaling
* Train-test split
* Logistic Regression model training
* Model evaluation using Accuracy, Precision, Recall, F1-Score, Confusion Matrix
* Visualization of ROC Curve and feature importance
* Model optimization using hyperparameter tuning (C) and regularization (L1, L2)



 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn



Evaluation Metrics

* Regression: MSE, RMSE, R² Score
* Classification: Accuracy, Precision, Recall, F1-Score, ROC-AUC



---
