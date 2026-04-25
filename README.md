# Logistic Regression with Gradient and Hessian Analysis

## Project Overview

This project implements logistic regression from scratch to perform binary classification on a breast cancer dataset. The focus is on understanding the mathematical foundations of the model, including the loss function, gradient, and Hessian matrix.

The objective is to analyze how different parameter vectors affect classification performance and decision boundaries.

## Objectives

* Implement logistic regression without using high-level ML libraries
* Compute and analyze the loss function
* Derive and implement the gradient and Hessian
* Visualize data and decision boundaries
* Evaluate different parameter configurations

## Methodology

* Data loading and preprocessing
* Exploratory visualization (scatter plot with class labels)
* Implementation of logistic (sigmoid) function
* Loss function computation (log-likelihood)
* Gradient calculation
* Hessian matrix computation
* Evaluation of different parameter vectors
* Visualization of decision boundaries

## Results

The analysis shows that parameter vectors with lower loss values produce better separation between classes. Additionally, smaller gradient magnitudes indicate proximity to optimal solutions, and the Hessian matrix confirms the convexity of the problem.

## Tech Stack

* Python
* NumPy
* Matplotlib

## Repository Structure

* `notebooks/`: exploratory analysis and visualization
* `src/`: implementation of functions (loss, gradient, Hessian)
* `data/`: dataset used for training
* `images/`: generated plots and visualizations

## Author

Andres Rico Quintero
