Car Price Predictor Project

This project is a machine learning application designed to predict the selling price of used cars based on various features such as brand, year, mileage, and fuel type. The dataset is sourced from Quikr and contains detailed information about cars listed for sale.

Features

Data Preprocessing: Handles missing values, outliers, and inconsistent data formats.

Exploratory Data Analysis (EDA): Provides insights into the dataset with visualizations.

Machine Learning Model: Implements regression algorithms to predict car prices.

Interactive Visualizations: Uses Matplotlib to create insightful plots.

Dataset

The dataset quikr_car.csv contains the following columns:

name: The model and make of the car.

company: The manufacturer of the car.

year: The year the car was manufactured.

Price: The listed price of the car (may contain inconsistencies).

kms_driven: The distance the car has been driven (e.g., "45,000 kms").

fuel_type: The type of fuel used (e.g., Petrol, Diesel).

Steps in the Project

Data Loading:

Load the dataset into a pandas DataFrame.

Data Cleaning:

Handle missing values in kms_driven and fuel_type columns.

Convert categorical data to numerical values using encoding techniques.

Clean and convert Price and kms_driven columns to numeric format.

EDA:

Analyze the distribution of features.

Visualize relationships between car features and price.

Model Development:

Train regression models such as Linear Regression and Random Forest on the cleaned data.

Evaluate models using metrics like R-squared, Mean Absolute Error (MAE), and Mean Squared Error (MSE).

Model Deployment:

Optionally, deploy the model using Flask or Streamlit for real-time predictions.

Requirements

Python Libraries:

pandas

numpy

matplotlib

scikit-learn
