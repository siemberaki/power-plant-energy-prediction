# Power-Plant-Energy-Prediction

### Combined Power Output Prediction System

- Project Outcome: Predict the energy output from the combined cycle power plant with high accuracy. So better prediction can help optimize the power output.

- Project Output: Build a model that can Predict the energy output with RMSE of less than 5 units or a prediction with R2 score of more than 0.95.

- Model Task: Regression(Supervised Regression) task. Since we are predicting a continuous numeric value, it is regression task.

- Based on Accuracy, Interpretability, Complexity and Since it is Regression task I will try the following Algorithms that are suitable for regression supervised task.

    * Linear Regression
    * Ridge Regression
    * Random Forest
    * XGBOOST

- Model Evaluation: Since the problem is a regression task, I will try RMSE(Root Mean Squared Error) because it is popular for regression tasks and also R2_Score which will explain the variation score of the targer prediction from the real value. So the evaluation metrics are:

    * RMSE (Root Mean Squared Error)
    * R2_SCORE (Coefficient of Determination)


#### Features

    - Temperature (T)
    - Ambient Pressure (AP)
    - Relative Humidity (RH)
    - Exhaust Vacuum (V)
    - Net hourly electrical energy output (PE)

# power-plant-energy-prediction
