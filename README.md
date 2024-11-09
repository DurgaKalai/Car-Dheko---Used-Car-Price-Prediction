# Car-Dheko---Used-Car-Price-Prediction
# Domain:
- Automotive Industry , Data Science, Machine Learning
# Project Scope:
- The project involves historical used car price data from CarDekho, including features like make, model, year, fuel type, transmission, and city. The goal is to build a machine learning model that predicts car prices based on these attributes and integrate it into a Streamlit web app, allowing users to input car details and receive instant price estimates.

# Skills Gained from This Project:
- Data Cleaning and Preprocessing:
Handling missing data, outliers, and feature encoding.
- Exploratory Data Analysis (EDA):
Visualizing data patterns and correlations.
- Machine Learning Model Development:
Building and training regression models.
- Price Prediction Techniques:
Applying regression algorithms for price estimation.
- Model Evaluation and Optimization:
Evaluating model performance and tuning hyperparameters.
- Model Deployment:
Deploying models for real-time predictions.
- Streamlit Application Development:
Creating interactive web apps to input data and display results.
- Documentation and Reporting:
Documenting the process and presenting results.

# Model Performance results
![model comparision](https://github.com/user-attachments/assets/00cf6b5c-bcc1-4be2-8357-2f8701b6e937)
- The RandomForestRegressor seems to be the best model for this data based on the R² and other evaluation metrics (MAE, MSE, RMSE). LinearRegression seems to be significantly underperforming, possibly due to overfitting or poor model assumptions.
- The RandomForestRegressor has the highest R² score and performs well across all metrics, making it the best model for model deployment.
- The best parameters for the RandomForestRegressor after grid tuning (Hyperparameter tuning) are expected to significantly improve model performance, and the best score of 0.86097 shows a solid fit. This configuration should lead to more accurate predictions.

# Screenshot of Streamlit app:
![screenshot 1](https://github.com/user-attachments/assets/a97fe034-fe16-4d68-8516-9e450ee78f12)


![screenshot 2](https://github.com/user-attachments/assets/57d0a373-b756-4503-8726-e83cac80c076)



