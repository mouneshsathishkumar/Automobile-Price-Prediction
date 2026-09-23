# Automobile-Price-Prediction
Machine learning project for predicting automobile prices using Linear Regression and Random Forest Regression.
Auto Price Prediction

File: AutoPricePrediction.ipynb

Objective

Predict the price of a used car based on its technical specifications (engine size, horsepower, mileage, brand, etc.) using regression models.

Workflow
Loaded and cleaned the auto_imports dataset
Performed EDA — price distribution, correlation of engine size/horsepower with price
Split data into 80% training and 20% testing (random_state=42)
Trained two models:
Linear Regression (baseline)
Random Forest Regressor
Evaluated models using R² Score
Identified top features influencing car price using Feature Importance
Results
Model	R² Score
Linear Regression	0.911
Random Forest Regressor	0.927

Key Insight: Engine size and horsepower have the strongest positive correlation with car price. Random Forest outperformed Linear Regression, making it the recommended model for this task.
