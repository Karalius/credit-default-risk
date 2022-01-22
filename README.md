# Home Credit Group Default Risk
![Home Credit](https://i.imgur.com/m0dRGEO.png)

This project consists of 3 notebooks which are located in ```Home Credit Group Default Risk``` folder.

Furthermore, each part of the project is briefly described in the sections below.

## EDA

One of the first goals here is to explore all given .csv files, understand relationships between those tables. Next goal is to perform visualizations to comprehend the data and gain insights into the variables potentially contributing to the default risk of the borrower. Finally, EDA notebook plays a crucial role for feature engineering, outlier detection, and variable encoding choices.


## Data Wrangling

This notebook takes insights from EDA and transforms the data. 
In this transformation data is cleaned from extreme outliers, new features are engineered, correlated features are dropped, and much more!

## Modelling

The last and most important part of this project - modelling notebook. Here, transformed and cleaned data is used to build powerful machine learning algorithms. Later, those algorithms are tuned with RandomizedSearchCV or Bayesian Optimization tools. Finally, these models are compared based on their accuracy and speed!
