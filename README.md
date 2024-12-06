# ML_Income_Classifier_Using_UCI_Adult_Data_Set


## Overview

This repository contains R code applying various machine learning algorithms to a data set. The data is census income from 1994 with the intention of predicting when the income of an individual exceeds $50k/year. 

The code is in the file Holland_Andrew_HW3.R

I'm trying to clean the dataset initially, removing several variables unnecessary for my analysis. Then, I clean the variables I do want to use, making some binary and standardizing others. Next, I perform some intial data analysis to understand what my data may be saying before applying machine learning. I split the data into training and validation sets using a 70:30 split and implement ridge and lasso regression models on income. Finally, I also implement a random forest model on income. From these results, I evaluated the different mnodels and found XYZ model was the most accurate when testing this dataset. 

This was homework for my ECON 418, Introduction to Econometrics course at the University of Arizona
