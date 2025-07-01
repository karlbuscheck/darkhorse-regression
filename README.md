# Comparing Ridge, Lasso, Elastic Net -- and a Dark Horse Model

## Project Overview

In this notebook, we'll dig into Ridge Regression, Lasso Regression, and Elastic Net using the `fetch_california_housing` dataset from Scikit-learn. By far, one of the coolest parts of this notebook is exploring -- and visualizing -- how Lasso operates as a powerful tool for feature selection. Ultimately, we'll compare the performance of all three models, only to find that a dark horse model proves the most powerful of all.

Here's the trail we'll be following:

## The Pipeline:

**Part 1: Ridge Regression**
- Import libraries and load the dataset
- Set X and y, the features and target
- Visualize the dataset: Plot first, model second
- Run Ridge Regression
- Tune the hyperparameter
- Compare and visualize the results of GridSearchCV
- Run Ridge Regression *with* polynomial features
- Tune the hyperparameter with polynomial features
- Compare and visualize the results of GridSearchCV *with* polynomial features
- Explore and visualize the Ridge Regression coefficients
- Visualize the learning curve or how Ridge coefficients shrink as `alpha` increases
- Perform grid search on preprocessing steps and model parameters

**Part II: Lasso Regression**
- Run Lasso Regression
- Use Lasso Regression to *effectively* perform feature selection

**Part III: Elastic Net**
- Run Elastic Net
- Visualize the grid search results for Elastic Net
- Compare the performance of Ridge, Lasso, and Elastic Net
- Evaluate the performance of a dark horse model

## Tools & Libraries Used

- **Jupyter Notebook** — the interactive environment used to explore, build, and document the entire modeling process   
- **Python 3.12.7** — base language powering all modeling, iteration, and data prep   
- **scikit-learn** - for linear and polynomial regression, preprocessing, feature scaling, pipelines, hyperparameter tuning (GridSearchCV), and model evaluation
- **matplotlib** - for data visualization, including learning curves, model performance, and coefficient behavior
- **seaborn** - for enhanced visualization and clearer comparisons across model results
- **pandas and numpy** - for data manipulation and analysis


## Acknowledgements

This notebook builds on a lecture by Tao Li, Associate Professor in the Department of Information & Analytics at Santa Clara University's Leavey School of Business. Many thanks to Professor Li for delivering lectures that spark continued exploration.
