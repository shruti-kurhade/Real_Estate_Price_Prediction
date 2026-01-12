# Bangalore House Price Prediction

A machine learning project that predicts house prices in Bangalore based on user inputs such as location, total square feet, number of bedrooms (BHK), and bathrooms.  
This project demonstrates an end-to-end data science workflow, including data preprocessing, model building, and deployment using a Flask API.

---

## Project Overview

Real estate pricing depends on many factors like area, locality, and house configuration.  
This project uses historical Bangalore housing data to train a regression model that can estimate house prices accurately.

The project covers:
- Data cleaning and feature engineering
- Machine learning model training
- Model serialization
- REST API development for predictions

---

## Technologies Used
- Python
- Numpy and Pandas for data cleaning
- Matplotlib for data visualization
- Sklearn for model building
- Jupyter notebook, visual studio code 
- Python flask for http server
- HTML/CSS/Javascript for UI

---

## Machine Learning Workflow
1. *Data Cleaning*
   - Removed missing and inconsistent values
   - Handled outliers
2. *Feature Engineering*
   - One-hot encoding for categorical features (location)
3. *Model Training*
   - Trained regression models
   - Selected best model based on performance
4. *Deployment*
   - Built Flask API to serve predictions
