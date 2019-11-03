# Data Driven Modelling

## Overview
This repository contains the work done as a part of the ENM 531: Data Driven Modelling course at Upenn 

## Dependencies
- Numpy
- Scipy
- Matplotplib
- PyDOE

## Projects

### 1 MLE and MAP estimates for weights w using different types and numbers of features

run mle\_map/MLE\_MAP\_estimates.ipynb

### 2 Optimisation and Logistic Regression

MLE estimates on a linear regression model with M fourier features and a gaussian likelihood
Implementation: Implemented Adam Optimizer from scratch and computed the MLW estimate for both regression weights and noise variance using SGD for 10000 iterations and learning rate 10\^-3

run opt\_logistic\_regression/mle\_est\_on\_LR\_model.ipynb

Given the data from 10000 simulated scenarios, modeled if an electrical grid is stable or not. Implemented a logistic regression model and computed the MLE estimate for the model weights by minimizing the binary cross-entropy loss using stochastic gradient descent updates with the Adam optimizer.

First 75% of data was used as train and the rest was used as test.

Achieved 79.95% accuracy

run opt\_logistic\_regression/electrical\_grids.ipynb
### 

