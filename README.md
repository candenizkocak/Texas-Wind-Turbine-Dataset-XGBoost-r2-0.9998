# Wind Turbine Power Generation Dataset Analysis

## Overview

This repository contains a data science project focused on predicting the power output. The dataset used in this project is a full-year hourly time-series simulated using the National Renewable Energy Laboratory (NREL) software for a location in Texas, US.

## About the Dataset

### Problem Statement

The intermittent nature and low control over wind conditions present challenges to grid operators in successfully integrating wind energy to meet current demand. Predicting the availability of wind generation plants in the next hour, day, or week is essential for balancing supply and demand. Incorrectly scheduling wind generation plants can lead to unnecessary reservations, increased costs passed on to consumers, and reliance on more expensive and polluting power resources.

### Dataset Details

- **Source**: [Texas Wind Turbine Dataset (Simulated)](https://www.kaggle.com/datasets/pravdomirdobrev/texas-wind-turbine-dataset-simulated)
- **Features**: The dataset contains various weather features that can be used as predictors.
- **Time Series**: Full-year hourly time-series
- **Location**: Texas, US
- **Turbine Details**: General Electric Wind Turbine installed onshore with the following specifications:
  - Rotor diameter: 111m
  - Rated output: 3600kW
  - Hub height: 80m

The dataset has perfect data completeness with no noisy data, which eliminates some of the challenges typically associated with working with real datasets.

### Evaluation Metrics

A good solution will include a simple baseline model and a more advanced forecasting approach. Visualization of both models on the same graph is recommended.

Recommended evaluation metrics include:

- Root Mean Square Error
- r2 Score

## Results

The project achieved an R2 score of 0.9998 using the XGBRegressor model.
