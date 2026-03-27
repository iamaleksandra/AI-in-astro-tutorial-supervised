# Air Quality Tutorial: Classification and Regression

This repository contains a teaching notebook based on the **Air Quality** dataset.

The notebook introduces two common supervised learning tasks using the same real-world dataset:

- **classification**, where continuous pollutant measurements are converted into categorical air-quality labels
- **regression**, where the goal is to predict a continuous pollutant concentration

The material is designed for teaching purposes and presents a practical machine-learning workflow on tabular data.

## Files

- `classification_regression_tutorial.ipynb` — main tutorial notebook
- `requirements_tutorial.txt` — Python packages required to run the notebook

## Dataset

The tutorial uses the **Air Quality** dataset, which contains hourly measurements collected by a gas sensor device in an Italian city from March 2004 to February 2005.

The dataset includes:
- sensor responses
- reference pollutant concentrations
- environmental variables such as temperature and humidity
- date and time information

## Topics covered

### Classification
The classification part of the notebook includes:
- transforming continuous pollutant measurements into categorical classes
- train/validation/test split with **stratification**
- preprocessing and feature scaling
- classification metrics
- training and comparing several models
- basic hyperparameter tuning
- model interpretation with feature importance and SHAP

### Regression
The regression part of the notebook includes:
- defining a continuous pollutant target
- time-based train/validation/test split
- regression metrics
- XGBoost regression
- quantile regression for predictive intervals

## Environment setup

This tutorial was prepared with **Python 3.11**.

Install the required packages with:

```bash
pip install -r requirements_classification_tutorial.txt
