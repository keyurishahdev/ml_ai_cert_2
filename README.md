This is the project for Machine learning certification course by berkley 

Practical Application Assignment 11.1: The original dataset contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure speed of processing. Your goal is to understand what factors make a car more or less expensive. As a result of your analysis, you should provide clear recommendations to your client -- a used car dealership -- as to what consumers value in a used car.
Here is the notebook link for the analysis that was done for this project - 

Problem statement - For a used car dealership they need to estimate selling price of a car. These prices can be estimated based on historical proces Lots of car prices are driven by make, model, year and condition of the car. If we are able to use the historical data and predict some prices.

Another intention of this excercise can be if the delaership needs to buy some cars what clients value. Are certain makes and model more popular? Do people prefer gas cars? Based on the above data we can provide some guidance to dealership on what they can keep more on stock.

Approach - I first cleaned up all thr data that is not needed. Scaled and extrapolate on all columns that will be used for model building. Built few models and then determined the best model 

Detailed Analysis - 
I did all the data analysis and tried to answer few questions based on data. I then used ['year', 'cylinders', 'odometer'] numerical columns and ['year', 'fuel', 'odometer', 'title_status', 'transmission','type'] non numerical columns. 
Non numerical columns were converted to binary. All nulls were replaced using immuter and frequently used data. 

I then split tha into 80% training and 20% test data. I then used the data set to train 'Linear Regression','Ridge Regression','Random Forest Regressor','AdaBoost Regressor', 'GradientBoostingRegressor'  models. Based on the analysis linear regression came to be best model

Next steps - 
We should run this against actual validation dataset and see if our model fits.
Also expand the selection to include state, make, model etc 
