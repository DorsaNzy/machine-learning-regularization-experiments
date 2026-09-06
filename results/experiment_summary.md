# Experiment Summary

## Project Title

Applied Machine Learning Experiment: Regularization, Bias-Variance, and Decision Boundaries

## Overview

This project contains two applied machine learning experiments focused on regularized regression and regularized classification.

## Part 1: Regularized Linear Regression

The first notebook studies model complexity using a water-level dataset. It compares a simple linear regression baseline with polynomial regression and evaluates how regularization affects model fit.

Main concepts demonstrated:

- Linear regression cost and gradient
- Polynomial feature expansion
- Feature normalization
- Learning curves
- Bias-variance behavior
- Validation error and test error
- Regularization tuning

Selected outputs:

- Linear regression baseline final cost: 22.37
- Polynomial regression test error with lambda = 3: 3.57
- Cross-validation selected lambda: 0.3
- Final test error in cross-validation experiment: 5.119

## Part 2: Regularized Logistic Regression

The second notebook studies binary classification using microchip quality-assurance data. Polynomial feature mapping is used to enable nonlinear classification boundaries, and regularization is used to control model complexity.

Main concepts demonstrated:

- Logistic regression cost and gradient
- Sigmoid-based binary classification
- Polynomial feature mapping
- Regularized optimization
- Nonlinear decision-boundary visualization
- Regularization strength comparison

Selected outputs:

- Polynomial feature matrix shape: 118 × 28
- Initial logistic regression cost: 0.693
- Final logistic regression cost: 0.260

## Portfolio Value

This repository demonstrates practical understanding of model implementation, regularization, validation-based model selection, model complexity, and visualization of learning behavior.
