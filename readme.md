# Linear Regression with Stochastic Gradient Descent (SGD) and Gradient Descent

This repository contains a Python implementation of linear regression using two different optimization techniques: Stochastic Gradient Descent (SGD) and Gradient Descent. It demonstrates how to train a linear regression model with a small dataset.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Implementation](#implementation)
- [Usage](#usage)
- [Results](#results)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Linear regression is a fundamental machine learning algorithm used for modeling the relationship between a dependent variable (target) and one or more independent variables (features). In this project, we implement linear regression using two optimization techniques:

1. **Stochastic Gradient Descent (SGD):** SGD is an iterative optimization algorithm that updates the model's parameters with a single training example at a time. It's well-suited for large datasets and online learning.

2. **Gradient Descent:** Gradient Descent is another optimization technique that updates the model's parameters using the gradients of the loss function with respect to all training examples. It's commonly used for batch learning.

## Dataset

The dataset used in this project is a small example dataset. It consists of [describe your dataset here, including its features and target variable]. You can find the dataset in the [dataset folder](./data.csv).

## Implementation

- `linear_regression_sgd.py`: This script contains the implementation of linear regression using Stochastic Gradient Descent (SGD).
- `linear_regression_gradient_descent.py`: This script contains the implementation of linear regression using Gradient Descent.

## Usage

To run the code and train the linear regression models, follow these steps:

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/linear-regression-sgd-gradient-descent.git
   cd linear-regression-sgd-gradient-descent
