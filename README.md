# Seoul-Bike-Rental-Prediction
Seoul Bike Rental Prediction

Seoul Rental Bike prediction
Executive Summary
Introduction
In this project, the objectives were to implement a gradient descent algorithm and utilise it to predict the number of bikes rented per hour. This report details the various experiments conducted using the dataset to understand the effect of tuning hyperparameters of the gradient descent algorithm. Also, the effect of the use of various independent variables/ features in prediction is evaluated and the best model was selected through experimentation.
About the Data
The dataset consists of 14 features and 8760 records. T
• Optimizing Hyperparameters like learning rate and convergence threshold improve accuracy and time taken to converge.
• Sensible feature selection and engineering improves prediction accuracy.
• Humidity measures in kitchen, living room and teenager room are best predictors in both
linear and logistic model. – need to change
• Prediction accuracy can be further improved by transforming the target variable with a
function form to treat homoscedasticity of errors .
information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation,
he dataset contains weather
Snowfall, Rainfall),
the number of bikes rented per hour and date information. In order to
remove the serial correlation with time, hours variable is hot encoded and converted to
dummies and ran the model .
 Project Outline
The Project is outlined to have 3 parts:
Part 1 : Data Preparation and Exploratory Data Analysis
Part 2 : Use Linear Regression Model for Rental Bike count Prediction and Report equation
Part 3 : Implement the gradient descent algorithm with batch update rule and carry out experiments with different values of i) learning rate, ii) Threshold and report the best fit values, iii) Pick random 8 features and train model with best hyper parameters , iv)
Hand pick best 8 features based on our assumption and train model with best hyper parameters .
