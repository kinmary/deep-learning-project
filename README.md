# deep-learning-project - Mariia Kindratyshyn
##  Dataset Description: Abalone
Original Dataset: http://archive.ics.uci.edu/dataset/1/abalone

Donation Date: 11/30/1995

###  Objective:
The dataset aims to predict the age (if abalone is old) of abalone based on physical measurements, providing an alternative to the laborious and time-consuming process of determining age through microscopic examination of shell rings.

###  Goal:
Predict the age (old - young) of abalone from physical measurements

Rings + 1.5 = Age in years

Age: Old - 0, Young - 1

###  Primary information:
Subject Area: Biology

Associated Tasks: Classification, Regression

Feature Types: Categorical, Integer, Real

Instances: 4177

Features: 8

Missing Values: No missing values exist in the dataset.

###  Variables Table:
The dataset comprises features including Sex, Length, Diameter, Height, Whole_weight, Shucked_weight, Viscera_weight, Shell_weight, and Rings (target variable).

Sex: Categorical variable with values M, F, and I (infant)

Length: Continuous variable, representing the longest shell measurement in mm

Diameter: Continuous variable, perpendicular to length in mm

Height: Continuous variable, measured with meat in shell in mm

Whole_weight: Continuous variable, representing the weight of the whole abalone in grams

Shucked_weight: Continuous variable, denoting the weight of the meat in grams

Viscera_weight: Continuous variable, representing gut weight after bleeding in grams

Shell_weight: Continuous variable, representing the weight of the shell after being dried in grams

Rings: Target variable, an integer representing age in years (+1.5)

##  Goal and Objectives
Goal: The overarching goal of this project is to develop a predictive model to estimate if abalone is young using easily obtainable physical measurements, thereby replacing the labor-intensive process of age determination involving microscopic analysis of shell rings.

###  Objectives:

Data Preparation and Exploration: Explore the dataset statistically and visually to understand feature distributions, correlations, and potential insights.

Model Development: Build and train models using appropriate approaches such as k-NN, MLP and LSTM. Evaluate models using suitable metrics like Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), or accuracy, precision, depending on the nature of the model.

Model Optimization: Employ cross-validation methods to ensure model robustness and generalization.

Performance Evaluation: Assess model performance using the baseline metrics established from the dataset description.
