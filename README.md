# MLB-Season-Ending-Statistics-Predictors
This repository contains a project that predicts the final value of certain baseball statistics at the end of the 2021 baseball season. 
The project uses pre-processed data to explore the best ways to make predictions.

# Prediction Process
The prediction process involves predicting the amount of HR per player in the 2016 season, then predicting the amount of HR per player in 2017. 
The data from these two seasons is combined to predict the amount of HR per player in 2018. The data from 2016, 2017, and 2018 is then used to 
predict HR per player in 2019. Finally, the results from 2019 are used to make the prediction for 2021. This process is repeated for other features 
such as OBP, RBI, and AVG.

# Models
The project uses three prediction models: Linear Regression, XGBoost, and KNN. The predictions were then checked against the actual values to evaluate 
the accuracy of the models.

# How to Use
To use this project, simply clone the repository and run the Jupyter notebook containing the code.
The notebook contains step-by-step instructions for pre-processing the data and making predictions using the three models.
