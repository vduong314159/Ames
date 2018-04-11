# Ames

You can see my final work [here](https://github.com/vduong314159/Ames_Iowa_Dataset/blob/master/ipynb/Ames-Lasso-Model.ipynb).

## Skills/Tools Used
Python (SciKit Learn, Numpy, Pandas, etc.)  
Jupyter notebooks  
Statistics  
Linear Algebra  
Data Transformation  
Data Normalization  
Regression Modeling (e.g. Ordinary Least Squares, LASSO, Ridge, Decision Tree Regression, Support Vector Machines)  Principle Component Analysis  
Data Visualization  
Clustering Models (eg K-Nearest Neighbors)

## Domain
This problem is drawn from the analysis of housing data.

## Problem Statement
Given certain information about houses sold in Ames, IA, we will use supervised learning to develop a linear regression model that can predict the selling price of a home.

## Dataset & Inputs
The dataset contains information from the Ames Assessor's Office used in computing assessed values for individual residential properties sold in Ames, IA from 2006 to 2010. Kaggle did some data cleaning to host a competition based on modeling and not data preparation.  

## Solution Statement
A solution to this problem will be a linear regression model with an L1-penalty, a lasso model. 

## Benchmark Model
Given that we seek a regression model, a good naive benchmark would be to use either the mean or the median of the wages for the dataset.

## Evaluation Metrics
Given that this is a regression task, we can measure the success of our model using the <a href="https://www.codecogs.com/eqnedit.php?latex=R^2" target="_blank"><img src="https://latex.codecogs.com/gif.latex?R^2" title="R^2" /></a> metric. 