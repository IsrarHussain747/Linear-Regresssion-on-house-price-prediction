House Price Prediction Using Linear and Polynomial Regression

Overview

This project implements a predictive model for estimating house prices using Linear Regression and Polynomial Regression. The dataset contains multiple socioeconomic and real estate-related features that influence housing prices. The models are evaluated using standard regression metrics.

Dataset

The dataset includes the following features:

CRIM: Crime rate per capita

ZN: Proportion of residential land zoned for large lots

INDUS: Proportion of non-retail business acres per town

CHAS: Charles River dummy variable (1 if tract bounds river, 0 otherwise)

NOX: Nitrogen oxide concentration

RM: Average number of rooms per dwelling

AGE: Proportion of owner-occupied units built before 1940

DIS: Weighted distances to employment centers

RAD: Accessibility index to radial highways

TAX: Property tax rate per $10,000

PTRATIO: Pupil-teacher ratio

B: Proportion of Black residents

LSTAT: Percentage of lower-status population

Price: Median value of owner-occupied homes (target variable)

Installation

Clone the repository:

git clone https://github.com/your-username/housing-price-prediction.git
cd housing-price-prediction

Install dependencies:

pip install -r requirements.txt

Usage

Load the dataset and preprocess it.

Train a Linear Regression model.

Train a Polynomial Regression model (degree = 2).

Evaluate models using MAE, MSE, and R² score.

Visualize actual vs predicted prices.

Run the script:

python house_price_prediction.py

Results

Linear Regression Performance:

MAE: 3.19

MSE: 20.52

R²: 0.68

Polynomial Regression (Degree=2) Performance:

MAE: 2.81

MSE: 15.72

R²: 0.78
