# California Housing Price Prediction

## Overview
This project is based on a tutorial from the book *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow*. It focuses on predicting housing prices in California using machine learning techniques such as Linear Regression and Random Forest Regression. The aim is to develop a model that can accurately estimate the median house value based on various features such as location, population, number of rooms, and other relevant attributes.

## Dataset
The dataset used in this project is the California Housing dataset, which includes information on various attributes of California homes collected from the 1990 census. It contains the following features:

- **latitude**: Block group’s latitude
- **longitude**: Block group’s longitude
- **households**: Average number of household members
- **median_house_value**: Median value of houses in block group
- **median_income**: Median income in block group
- **housing_median_age**: Median house age in block group
- **total_rooms**: Average number of rooms per household
- **total_bedrooms**: Average number of bedrooms per household
- **population**: Population in block group

## Project Structure
- **Housing.ipynb**: Jupyter notebook containing the exploration, visualization, and model development process.
- **Housing.tgz**: Dataset used in the project.

## Features
The following features have been engineered and added to improve model performance:
- **rooms_per_hhold**: The average number of rooms per household.
- **pop_per_hhold**: The average number of people per household.
- **bedrooms_per_room**: The ratio of bedrooms to rooms.

## Model Evaluation
The model's performance is evaluated using various metrics including:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

## Results
The final model achieved a performance of:
- **RMSE**: 48210.41

These results indicate that the model is able to make reasonably accurate predictions on the test data.
