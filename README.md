# NYC-Taxi-Trip-Time-Prediction
# Problem Description
Task is to build a model that predicts the total ride duration of taxi trips in New York City. Primary dataset is one released by the NYC Taxi and Limousine Commission, which includes pickup time, geo-coordinates, number of passengers, and several other variables.
#  Project Files Description
This repository includes 1 colab notebook (.ipynb) file and 1 pdf file of project presentation.

About Files:
NYC Taxi Trip Time Prediction Capstone Project.ipynb - This file includes Features description, exploratory data Analysis, feature engineering, feature scaling and implemented algorithms for eg. Linear Regression, Decision Tree, XGBoost.
NYC_PPT - This is a power point presentation file of a project. It includes various visualaized plots of EDA using Seaborn and Matplotlib. The result chart of various implemented algorithms.
# Summary
The given dataset conatins more than 14 lac records and 11 columns. The main goal of this project to predict the trip duration. To get more insights about the dataset, performed Exploratory data analysis to understand the main characteristics of various features. Using existing features, created new features for model building and to interpret data more easily. After analyzing the dataset, it’s found that there is a some inconsistency in some recorded data. The passenger count was high like 7 to 9 passengers in taxi. The travelled distance is very less but trip duration is quite high. There were many outliers in many columns and after analyzing the data, those outliers removed and dataset prepared for model building. Various algorithms apllied on prepared dataset afetr train and test split of dataset. Linear Regression algorithm performed very poorly on given dataset. It predicted 0.60 R2 score on train and test dataset. Decision Tree predicted 0.99 for Train dataset and 0.49 for test. It’s observed that its a overfitting model. XG Boost predicted good accuracy on train and test dataset. It predicted 0.77 and 0.76 R2 score.
