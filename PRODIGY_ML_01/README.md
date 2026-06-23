# House Price Prediction using Linear Regression

## Task Overview

This project implements a Linear Regression model to predict house prices based on:

* Square Footage (Living Area)
* Number of Bedrooms
* Number of Bathrooms

The model is trained using the House Prices dataset from Kaggle.

## Dataset

Dataset: House Prices - Advanced Regression Techniques

Source:
https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

File Used:

* train.csv

## Features Used

| Feature      | Description                            |
| ------------ | -------------------------------------- |
| GrLivArea    | Above ground living area (square feet) |
| BedroomAbvGr | Number of bedrooms                     |
| FullBath     | Number of full bathrooms               |
| SalePrice    | House selling price (Target Variable)  |

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Jupyter Notebook

## Project Structure

```text
PRODIGY_ML_03/
│
│
└── Task_01/
    ├── Task 01.ipynb
    ├── README.md
    └── requirements.txt
```

## Installation

Clone the repository:

```bash
git clone <repository-url>
```

Navigate to the project folder:

```bash
cd PRODIGY_ML_03/Task_01
```

Install required dependencies:

```bash
pip install -r requirements.txt
```

## Model Workflow

1. Load the dataset.
2. Select relevant features.
3. Split the dataset into training and testing sets.
4. Train the Linear Regression model.
5. Predict house prices.
6. Evaluate model performance.

## Evaluation Metrics

The model is evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

## Results

The model successfully predicts house prices based on living area, bedrooms, and bathrooms. The evaluation metrics provide insights into the prediction accuracy of the model.

## Future Improvements

* Use additional house features.
* Perform feature engineering.
* Compare with other regression algorithms.
* Deploy the model as a web application.

## Conclusion

This project demonstrates the implementation of a Linear Regression model for house price prediction. It covers data preprocessing, model training, prediction, and performance evaluation using real-world housing data.

## Author

Aayush Kumar Jha

Machine Learning Internship - Task 01
