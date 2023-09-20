# Random Forest Regressor
This Jupyter notebook serves as part of the data science pipeline by providing a quick and easy framework to
perform feature enginnering, model training and feature importance analysis for data exploration. In this particular notebook,
Sci-Kit Learn's RandomForestRegressor was trained on information regarding [housing in Perth](https://www.kaggle.com/datasets/syuzai/perth-house-prices) to
numerically predict house prices based on floor space, suburb, number of bedrooms, etc. Feature importance analysis was performed using 
built-in methods that calculate importance by node impurity. However, SHAP was also used to provide a more robust and in-depth analysis
via Shapley values.

## Features

- Model saving and loading.
- Hyperparameter tuning via Bayesian optimization.
- Feature importance analysis using tree node impurity and Shapley values.

## Future Improvements

- Custom user input to the model (involves writting a custom data encoder instead of using pandas.get_dummies()).
- Reducing the disk size of saved models.
