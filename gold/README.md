# Recovery of gold from ore

## Data
We have at our disposal data with mining and refining parameters, split into training and test samples. An initial data set is also provided. Some parameters are not available for model training because they are calculated at later stages of the production process. Because of this, the test sample is missing some attributes that may be in the training sample. Also, there are no target attributes in the test set.

## Purpose and Additional Objectives
The main objective within this project is to build models that predict the recovery rate of gold from gold-bearing ore at different stages of the production process: for the rough concentrate and for the final concentrate. 

In the course of the work it was necessary to solve a number of additional tasks:
- to check the correctness of the calculation of ore recovery efficiency (our target attribute) - it was necessary to make an independent calculation using the given formula, as well as to calculate the MAE metric between the data from the dataset as well as the results of our calculation;
- to study the variation of metal concentration at different stages of purification, to study the total concentration of substances at different stages of the production process, and to compare the distribution of some of the features in the training and test samples;
- define a function to be used as a metric for assessing the quality of the models.

## Libraries
- pandas
- numpy
- matplotlib, seaborn
- sklearn
