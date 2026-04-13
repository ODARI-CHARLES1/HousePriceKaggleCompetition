# Housing Prices Competition for Kaggle Learn Users

A machine learning competition to predict house prices using the Ames Housing dataset. This competition is part of Kaggle's Machine Learning course.

<img width="1356" height="100" alt="image" src="https://github.com/user-attachments/assets/92411343-5ac5-4059-a475-790f9d6a9717" />

[Leaderboard](https://www.kaggle.com/competitions/home-data-for-ml-course/leaderboard#)

## Competition Overview

Predict the sale price of houses based on various features describing residential properties.

## Dataset

- **train.csv**: Training data with features and target variable (SalePrice)
- **test.csv**: Test data for predictions
- **sample_submission.csv**: Submission format example

## Approach

- Data exploration and visualization
- Feature engineering
- Handling missing values
- Model training and evaluation
- Various regression techniques

## Getting Started

1. Download the competition data from [Kaggle](https://www.kaggle.com/competitions/home-data-for-ml-course)
2. Place the data files in a `data/` directory
3. Run the notebook or execute the training script

## Dependencies

- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost (optional)
- lightgbm (optional)

## Evaluation

Submissions are evaluated using Root Mean Squared Error (RMSE) between the logarithm of the predicted value and the logarithm of the actual sale price.
