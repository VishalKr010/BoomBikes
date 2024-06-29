# BoomBikes
Jupyter notebook for building a multiple linear regression model to predict demand for BoomBikes (US bike-sharing) post-pandemic. Analyzes factors impacting demand &amp; helps optimize business strategy.

BoomBikes Demand Prediction

This Jupyter notebook implements a multiple linear regression model to predict demand for BoomBikes, a US bike-sharing company. The model analyzes the impact of various factors on shared bike demand in the American market.

Problem Statement:

BoomBikes seeks to understand how the demand for shared bikes will change after the COVID-19 pandemic lockdowns end.

Business Goal:

The model will help BoomBikes:

Identify significant factors influencing demand
Understand how these factors affect demand levels
Develop a data-driven strategy to meet customer needs
Data:

The provided dataset includes daily bike demand data across the American market, along with various independent variables.

Data Preprocessing:

Categorical variables like "weathersit" and "season" will be converted from numerical to string values.
The "yr" column indicating years will be retained as it might influence demand trends.
Model Building:

A multiple linear regression model will be built using the "cnt" variable (total bike rentals) as the target variable.
Model Evaluation:

R-squared score will be calculated on the test set to evaluate model performance.
Getting Started:

Clone this repository.
Install required libraries (listed in the notebook).
Open the Jupyter notebook and run the cells.
Additional Notes:

Refer to the data dictionary for detailed information on independent variables.
Feel free to explore and improve this code!
