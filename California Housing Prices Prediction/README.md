# Linear Regression on California Housing Dataset

## Overview

This repository contains code for performing Linear Regression on the California Housing dataset, which is used in the second chapter of Aurélien Géron's book *Hands-On Machine Learning with Scikit-Learn and TensorFlow*. This dataset is a valuable resource for learning the basics of machine learning, particularly for introductory tasks involving data cleaning and model implementation.

## Dataset Description

The dataset is derived from the 1990 California census and provides information about housing in various districts. Although it may not be directly applicable to predicting current housing prices, it serves as an excellent starting point for teaching and practicing machine learning techniques. 

### Dataset Features

The dataset includes the following columns:

- **longitude**: Longitude coordinate of the house.
- **latitude**: Latitude coordinate of the house.
- **housing_median_age**: Median age of the houses in the district.
- **total_rooms**: Total number of rooms in the district.
- **total_bedrooms**: Total number of bedrooms in the district.
- **population**: Population of the district.
- **households**: Number of households in the district.
- **median_income**: Median income of the district.
- **median_house_value**: Median house value in the district.

### Data Cleaning

Please note that the dataset is not pre-cleaned and contains missing values. Data preprocessing steps such as handling missing values and scaling features are required before applying machine learning algorithms.

## Project Details

In this repository, we are focusing on applying Linear Regression to this dataset. The goal is to predict the median house value (`median_house_value`) based on other features in the dataset.

### Steps Included

1. **Data Loading**: Load the dataset from its source.
2. **Data Preprocessing**: Handle missing values, scale features, and prepare the dataset for modeling.
3. **Model Training**: Apply Linear Regression to the preprocessed data.
4. **Evaluation**: Assess the model's performance using appropriate metrics.
