![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Comparing regression models


For this lab, we will be using the same dataset we used in the previous labs. We recommend using the same notebook since you will be reusing the same variables you previous created and used in labs. 

### Instructions

1. In this final lab, we will model our data. Import sklearn `train_test_split` and separate the data.
2. Try a simple linear regression with all the data to see whether we are getting good results.
3. Great! Now define a function that takes the following arguments:

* list_of_models (functions of sklearn to train a model)
* the X_train
* the y_train
* the X_test
* the y_test

The function should do:

* train every model inside `list_of_models` on the train set
* make predictions with the trained models on the train and test sets
* provide error metrics (ME, MAE, MSE, RMSE, R2, R2_adj) of every model in the train and test sets

4. Use the function to check `LinearRegressor` and `KNeighborsRegressor`.
5. You can check also the `MLPRegressor` for this task!
6. Check and discuss the results.
