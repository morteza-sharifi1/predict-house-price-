# House price forecasting app

This repository contains a web app for predicting prices based on features using XGBoost. The app is built with Flask.

## Installation
To run the app locally, you'll need to have Python 3.x installed on your system. You can then clone this repository and install the necessary dependencies using pip:

git clone [https://github.com/yourusername/predict-house-price.git](https://github.com/morteza-sharifi1/predict-house-price-.git)
cd predict-price-app
pip install -r requirements.txt

## Usage
To start the app, run the following command:
python app.py

This will start a local web server at http://localhost:5000. You can then navigate to this URL in your web browser to access the app.

The app allows you to input values for various features (such as the number of bedrooms and bathrooms) and get a predicted price based on these values. The app uses XGBoost to make the predictions.

## Files
The repository contains the following files:

app.py: The Flask app code.
model.pkl: The trained XGBoost model.
requirements.txt: The list of Python dependencies required to run the app.
templates/index.html: The HTML template for the app.
static/css/styles.css: The CSS styles for the app.

## EDA
The first step in the project is to perform exploratory data analysis (EDA) on the dataset. This involves visualizing the data to understand the distribution of the features, identifying any outliers or missing values, and exploring the relationships between the features and the target variable.

## Feature Selection
the next step is to select the best features for predicting sales. This involves identifying the most important features that have the strongest relationship with the target variable, and discarding features that are redundant or less important.

## Model Building
After performing feature selection, the next step is to build and evaluate various models for predicting sales. This involves training and testing different machine learning models, such as **linear regression**, **Ridge**, **Lasso**, **BayesianRidge**, **ElasticNet**, **SGDRegressor**, **HuberRegressor**, **GradientBoosting**, **AdaBoostRegressor**, **ExtraTreesRegressor**, **RandomForestRegressor**, **BaggingRegressor**, **KNeighborsRegressor**, **DecisionTreeRegressor** and **XGBoost**, and selecting the best performing model based on various evaluation metrics, such as R-squared.

## Model Deployment
After selecting the best model, the final step is to deploy the model for predicting sales. This involves creating a final model using the entire dataset, and then saving the model as a serialized object that can be loaded and used for making predictions.
