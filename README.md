# House-Price-Prediction

A machine learning project that predicts house prices based on various features such as location, square footage, number of bedrooms, and more.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Performance](#model-performance)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project aims to build a predictive model using supervised learning to estimate the selling prices of houses. It's intended as a demonstration of data preprocessing, feature engineering, and model training using machine learning techniques.

## Features

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Feature engineering
- Model training and evaluation

## Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Dataset

The dataset used is the [Kaggle House Prices - Advanced Regression Techniques dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).  
It contains 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa.

## Installation

1. Clone the repository:
   bash
   git clone https://github.com/yourusername/house-price-prediction.git
   cd house-price-prediction
   
2. Input the house features to get a predicted price.

## Model Performance

| Model          | RMSE (Cross-Validated) |
|----------------|------------------------|
| Linear Regression | 0.137 |
| Random Forest    | 0.125 |
| XGBoost          | 0.118 |

Note: Metrics may vary depending on preprocessing and train/test split.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

## License

This project is open-source and available under the [MIT License]
