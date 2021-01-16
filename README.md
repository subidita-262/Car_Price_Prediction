# Car_Price_Prediction
## Project Description
Takes the information of Present price, distance driven, fuel type, age of the car, seller type etc. & evaluates the selling price.
Used the Random Forest Regression module of Machine Learning to train our model.
Selected 12 different decision trees in the range 100 to 1200 to train the model.
Deployed in Heroku.
## Modules used
Find the important features by ExtraTreeRegressor.
Present price is having highest importance.
Random Forest Regressor
Hyperparameter tuning to avoid over-fitting.
Selected different decision trees from 100 to 1200.
Randomized Search CV
Helps to find out best parameters.
Its faster than grid search cv
Create Random grid
Apply the selected parameters and fit to the training dataset.
Predict the selling price on X test dataset.
## Comparing Results
Using Distplot : difference between actual results and predicted results.
Normal distribution.
## Future Improvements
Train the model with more features to get more accurate results.
Use other modules for further improvements.
Minimize the errors.

deployed in heroku : https://car-price-predicton.herokuapp.com/
