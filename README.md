# House Price Prediction using Machine Learning

## Project Overview

This project predicts house prices using Machine Learning techniques based on various property features such as area, number of bedrooms, bathrooms, parking availability, furnishing status, and other amenities. The objective is to help real estate buyers, sellers, and businesses estimate property values more accurately using data-driven insights.

## Dataset

* Dataset: Housing Prices Dataset
* Source: Kaggle
* File Used: `Housing.csv`

The dataset contains information about residential properties and their corresponding prices.

## Objectives

* Perform data cleaning and preprocessing
* Explore the dataset through visualizations
* Build predictive models for house price estimation
* Compare Linear Regression and Random Forest Regression models
* Identify the most important factors influencing house prices

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Project Workflow

### 1. Data Exploration

* Loaded the dataset using Pandas
* Examined data structure and feature types
* Checked for missing values and duplicates

### 2. Data Cleaning

* Removed duplicate records
* Handled missing values
* Applied One-Hot Encoding to categorical variables

### 3. Model Development

* Linear Regression
* Random Forest Regressor

### 4. Model Evaluation

The models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### 5. Data Visualization

The project includes:

* House Price Distribution Histogram
* Correlation Heatmap
* Actual vs Predicted Price Scatter Plot
* Feature Importance Analysis

## Key Findings

* Property area was the strongest predictor of house price.
* Bathrooms, parking availability, air conditioning, and number of stories significantly influenced prices.
* Random Forest Regression outperformed Linear Regression in prediction accuracy.
* Homes with larger areas and additional amenities generally had higher market values.

## Business Recommendation

Real estate companies can improve pricing accuracy by focusing on property size and high-impact amenities during valuation. Machine Learning models can support more informed pricing decisions and reduce reliance on manual estimation methods.

## Repository Structure

HousePricePrediction/

├── analysis.ipynb

├── Housing.csv

├── HousePricePrediction_Summary.pdf

└── charts/

  ├── price_distribution.png

  ├── correlation_heatmap.png

  └── actual_vs_predicted.png

## Future Improvements

* Hyperparameter tuning
* Advanced ensemble models (XGBoost, Gradient Boosting)
* Deployment using Flask or Streamlit
* Interactive dashboard using Power BI or Tableau

