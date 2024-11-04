# House Price Prediction

## Overview

This project aims to predict house prices based on various features such as the number of rooms, location, square footage, and more. Using machine learning models, the goal is to provide accurate price estimates, which can be valuable for both buyers and sellers in the real estate market.

## Table of Contents
- Introduction
- Data
- Modeling
- Requirements
- Future Improvements
- Acknowledgements

## Introduction

The prices of houses are influenced by various factors like size, location, neighborhood, age, and quality of construction. Predicting house prices with high accuracy can greatly benefit real estate professionals, buyers, and sellers by helping them make data-driven decisions. This project uses historical data on house features and their selling prices to train a model capable of estimating house prices for new listings.

## Data

The dataset used for this project includes various features such as:

- LotArea:Lot size in square feet
- YearBuilt: Year the house was built
- TotalRooms: Total number of rooms above ground
- Neighborhood: Physical location of the property
- GrLivArea: Above ground living area in square feet
- GarageCars: Number of car spaces in the garage
- FullBath: Full bathrooms above ground level
- SalePrice: The target variable representing the sale price of the house

The dataset can be downloaded from [ Kaggle's House Prices: Advanced Regression Techniques.](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview)

## Modeling

Several machine learning models were tested and evaluated, including:

- Linear Regression: A basic linear approach to understand feature relationships.
- Random Forest Regressor: A tree-based ensemble model to capture non-linear relationships.
- Gradient Boosting Regressor: A boosting method that typically offers strong performance.
- XGBoost Regressor: A highly optimized and scalable model that provides state-of-the-art results for tabular data.
Evaluation metrics used:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
Hyperparameter tuning was conducted using cross-validation to improve model performance.

## Requirements

To run this project, install the dependencies in [requirements.txt](https://github.com/Karanshukl/House_price_prediction/blob/main/requirements.txt)

Requirements include:

- Python 3.7+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- xgboost


## Future Improvements

Future work can focus on:

- Feature engineering to create new meaningful features
- Hyperparameter tuning with more advanced techniques (e.g., Bayesian Optimization)
- Experimenting with more complex models or neural networks
- Adding external datasets (e.g., economic indicators, neighborhood crime rates)


## Acknowledgments

Special thanks to the Kaggle Community for providing the dataset and resources that made this project possible.


## Links 🔗
🔗 Github [karanshukl](https://www.github.com/karanshukl)  
🔗 Linkedin - [karanshukl](https://www.linkedin.com/in/karanshukl/)

Follow for more details :- [@karanshukl](https://www.linkedin.com/in/gkaranshukl/)
