# House Price Prediction using Linear Regression

## Project Overview
This project demonstrates how to use **Linear Regression** to predict house prices based on various features such as area, bedrooms, bathrooms, stories, and parking availability. The model is built and evaluated using Python and scikit-learn.

---

## Features

- Data preprocessing including handling missing values
- Splitting data into training and testing sets
- Training a Linear Regression model
- Evaluating model performance using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score (Coefficient of Determination)
- Interpretation of model coefficients to understand feature impact
- Visualization of regression results with scatter plots and regression lines

---

## Dataset

The dataset contains house price records with features such as:

- **price**: House price (target variable)
- **area**: Size of the house in square feet
- **bedrooms**: Number of bedrooms
- **bathrooms**: Number of bathrooms
- **stories**: Number of stories
- **parking**: Number of parking spots
- Additional categorical features like `mainroad`, `guestroom`, `airconditioning`, etc.

---

## Getting Started

### Prerequisites

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib

You can install the required packages with:

```bash
pip install pandas numpy scikit-learn matplotlib
