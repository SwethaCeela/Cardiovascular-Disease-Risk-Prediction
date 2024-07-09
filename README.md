# Cardiovascular Disease Risk Prediction

## Project Overview

This project aims to identify the causes of cardiovascular diseases and develop a system to predict heart attacks in an effective manner. The dataset used in this project contains information about various factors that might impact cardiovascular health.

## Experiment No. 1: Data Cleaning and Integration

In this experiment, we performed preliminary data inspection and reported the findings on the structure of the data, missing values, duplicates, etc. We then removed duplicates and treated missing values using an appropriate strategy.

## Experiment No. 2: Data Analysis and Visualization

In this experiment, we applied various data analysis and visualization techniques to the healthcare data. We:
- Obtained a preliminary statistical summary of the data and explored measures of central tendencies and spread of the data.
- Identified categorical variables and described and explored them using count plots.
- Studied the occurrence of CVD across the Age category.
- Studied the composition of all patients with respect to the Sex category.
- Analyzed the relationship between resting blood pressure and heart attacks.
- Described the relationship between cholesterol levels and a target variable.
- Explored the relationship between peak exercising and the occurrence of a heart attack.
- Checked if thalassemia is a major cause of CVD.
- Listed how other factors determine the occurrence of CVD.
- Used a pair plot to understand the relationship between all given variables.

## Experiment No. 3: Disease Risk Prediction

In this experiment, we built a baseline model to predict the risk of a heart attack using Linear/Logistic regression and random forest. We explored the results using correlation analysis and Linear/Logistic regression (leveraging standard error and p-values from stats models) for feature selection.

## Repository Structure

This repository contains the following files and folders:
- **data**: contains the original dataset used in the project
- **notebooks**: contains Jupyter notebooks for each experiment
- **reports**: contains reports for each experiment
- **models**: contains the trained models for disease risk prediction
- **README.md**: this file

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
