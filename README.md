# XGBoost_Regression

House Price Prediction using XGBoost Regression

This project focuses on predicting house prices using XGBoost Regression for a Kaggle-style competition.

Key Features & Methods:

Implemented XGBoost Regressor for accurate price prediction.

Tuned hyperparameters using GridSearchCV with 5-fold cross-validation to find the best combination:

param_grid = {
    "max_depth": [4, 5, 6],
    "n_estimators": [500, 600, 700],
    "learning_rate": [0.01, 0.015]
}


Used RMSLE (Root Mean Squared Logarithmic Error) as the evaluation metric to handle large value ranges.

Achieved best RMSLE score: 0.13914 on the training set with the optimized hyperparameters.

Workflow:

Performed hyperparameter tuning with GridSearchCV using 5-fold cross-validation.

Trained the final XGBoost model using the best-found parameters.

Evaluated model performance using RMSLE.

This repo demonstrates model selection, hyperparameter tuning, and evaluation using a robust regression technique suitable for real-world price prediction tasks.
