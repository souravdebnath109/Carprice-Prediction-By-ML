# Car Price Prediction Model

This project predicts the selling price of used cars based on various features such as car model, mileage, and age. Using this model, users can estimate the price of a car given its specifications, which can be useful for car sellers and buyers looking to understand the market value.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Model Training](#model-training)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

The Car Price Prediction model is a supervised learning project that uses historical data of car prices to train a regression model. Given the car's model, mileage, and age, the model predicts the estimated selling price of the car. This project demonstrates the application of machine learning for price estimation.

## Dataset

The dataset used in this project (`carprices.csv`) includes the following features:

- **Car Model**: Name of the car model (e.g., BMW X5, Audi A5, Mercedes Benz C Class)
- **Mileage**: The total distance the car has traveled (in miles)
- **Sell Price ($)**: The selling price of the car (in USD)
- **Age (yrs)**: Age of the car in years

### Sample Data

| Car Model               | Mileage | Sell Price ($) | Age (yrs) |
|-------------------------|---------|----------------|-----------|
| BMW X5                  | 69000   | 18000         | 6         |
| Audi A5                 | 59000   | 29400         | 5         |
| Mercedez Benz C class   | 67000   | 22000         | 6         |

## Features

- **Predict Car Prices**: Estimate the selling price of a car based on input features (car model, mileage, and age).
- **Regression Model**: Uses a regression algorithm to fit the data and make accurate predictions.
- **Flexible and Extensible**: Can be easily modified to include additional features or fine-tune model parameters.

## Images:
![Screenshot 2024-11-08 002253](https://github.com/user-attachments/assets/e87085b6-2aad-47fe-8b05-ca25ca3719ab)
![Screenshot 2024-11-08 002234](https://github.com/user-attachments/assets/955368c9-c2c8-4133-ae2e-6441a2c3405e)
![Screenshot 2024-11-08 002300](https://github.com/user-attachments/assets/1508a461-163f-47cd-9547-f9526bedfdc2)
![Screenshot 2024-11-08 002310](https://github.com/user-attachments/assets/0710d61c-0791-462e-9afe-aa67d53a27de)


## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/souravdebnath109/Carprice-Prediction-By-ML.git
   cd car-price-prediction
