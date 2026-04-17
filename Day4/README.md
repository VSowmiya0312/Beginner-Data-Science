House Price Prediction using Regression Models

Project Overview

This project is part of the **Data Science with AI Bootcamp (Day 4 Task)**.
The objective is to build and evaluate different regression models to predict house prices using real-world data.

Objectives

* Apply regression techniques on a real dataset
* Build:

  * Simple Linear Regression
  * Multiple Linear Regression
  * Polynomial Regression
* Evaluate model performance using standard metrics

Dataset

* 📊 Dataset: House Price Prediction
* 🔗 Link:
  https://raw.githubusercontent.com/nunnarilabs/ml/master/house/kc_house_data.csv

Technologies Used

* Python 
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

Models Implemented

1️⃣ Simple Linear Regression

* Uses a single feature: `sqft_living`
* Helps understand basic linear relationship with price

2️⃣ Multiple Linear Regression

* Uses multiple features from the dataset
* Provides better prediction accuracy by considering multiple factors

3️⃣ Polynomial Regression

* Uses polynomial features (degree = 2)
* Captures non-linear relationships in data

📈 Model Evaluation Metrics

Each model is evaluated using:

* 📉 Mean Squared Error (MSE)
* 📉 Mean Absolute Error (MAE)
* 📊 R² Score (Coefficient of Determination)

Key Insights

* House prices strongly depend on living area (`sqft_living`)
* Multiple features improve prediction accuracy significantly
* Polynomial regression captures non-linear patterns better than simple linear regression

Challenges Faced

* Encountered error due to non-numeric data (`date` column)
* Resolved by removing or converting non-numeric columns

Learning Outcomes

* Practical understanding of regression models
* Experience in handling real-world datasets
* Learned importance of data preprocessing
* Gained knowledge of model evaluation techniques

Acknowledgment

Thanks to **Nunnari Academy** for providing this hands-on learning experience through the Data Science Bootcamp.

