Yes Bank Stock Price Prediction – Project Summary
📌 Project Title:
Stock Price Prediction for Yes Bank using Machine Learning

🎯 Objective:
To develop a machine learning model that predicts the monthly closing stock price of Yes Bank, using historical data and features such as High, Low, Previous Close, year, and Month.

📁 Dataset Summary:
Real-world monthly stock data of Yes Bank

Key Features: High, Low, Prev_Close, Day, Month

Target Variable: Close (closing price of the stock)

🧹 Data Preprocessing:
Extracted Day and Month from Date

Created Prev_Close using a shift of the Close column

Handled missing values and scaled features for SVM

🧠 Models Used:
Linear Regression

Random Forest Regressor (tuned with RandomizedSearchCV)

Support Vector Machine (SVM) (with GridSearchCV)

XGBoost Regressor

📈 Evaluation Metrics:
Mean Squared Error (MSE)

R² Score (Coefficient of Determination)

🏆 Model Performance Summary:
Model	R² Score	MSE
Linear Regression	0.87	4.23
Random Forest	0.90	3.12
SVM	0.88	3.89
XGBoost ✅	0.91	2.97

🔹 XGBoost outperformed all other models, making it the most accurate choice for this dataset.

