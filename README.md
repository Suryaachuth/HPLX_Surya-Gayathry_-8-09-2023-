# HPLX_Surya-Gayathry_-8-09-2023-
data set used is URL: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

This project focuses on predicting the payment value for future purchases in an e-commerce business. It utilizes various data sources, data cleaning techniques, exploratory data analysis (EDA), feature engineering, and machine learning models to achieve this prediction.

In this project, we aim to predict the payment value for future purchases made by customers in an e-commerce platform. This prediction can help the business better understand customer behavior and plan its operations accordingly.

to run this project, you need the following Python libraries and dependencies:
pandas
numpy
seaborn
matplotlib
scikit-learn
xgboost
lightgbm
The project uses several datasets:

Customer Data
Geological Data
Review Data
Seller Data
Product Data
Orders Data
Order Item Data
Payment Data
These datasets are essential for performing data analysis, feature engineering, and training the machine learning models.

Data Cleaning
Data cleaning involves removing unnecessary columns and handling missing data. Key data cleaning steps include:
Dropping unnecessary columns in geological and product datasets.
Handling missing data in customer and payment datasets.

Exploratory Data Analysis 
EDA is performed to gain insights from the data. Key EDA tasks include:
Visualizing customer counts by state to identify the majority customer base.
Calculating the average delivery time to each state.
Identifying regions with longer delivery times.

Feature Engineering
Feature engineering involves creating new features or transforming existing ones to improve model performance. In this project, features related to order and payment data are engineered.

Most Valuable customers are found using RFM Score

Model Building
Machine learning models are used to predict payment values. The following models are evaluated:

AdaBoost Regressor
Gradient Boosting Regressor
Random Forest Regressor
Decision Tree Regressor
XGBoost Regressor
LightGBM Regressor
The models are trained and evaluated for both training and testing Mean Absolute Error (MAE).

Hyperparameter Tuning
Hyperparameter tuning is performed to optimize the XGBoost Regressor model. GridSearchCV is used to find the best hyperparameters for the model.

Model Serialization
The best-performing XGBoost model is serialized and saved for future use. Encoders used for label encoding are also saved for future data preprocessing.

Conclusion
This project demonstrates the process of predicting payment values for e-commerce customers. It includes data cleaning, exploratory data analysis, feature engineering, model building, hyperparameter tuning, and model serialization. The optimized model can be used for predicting payment values for future purchases.






