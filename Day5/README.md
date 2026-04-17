Titanic Survival Prediction using Machine Learning

Project Overview

This project focuses on predicting passenger survival on the Titanic using **Machine Learning**. The dataset contains information about passengers such as age, gender, ticket class, fare, and family details. The goal is to build a classification model that can accurately predict whether a passenger survived or not.

Objective

* Analyze the Titanic dataset
* Perform data preprocessing and cleaning
* Apply feature engineering techniques
* Build a **Logistic Regression model**
* Evaluate model performance using standard metrics
* Visualize insights using graphs

Dataset

The dataset used in this project is the Titanic dataset, which includes:

* Passenger details (Age, Sex, Class, etc.)
* Survival status (Target Variable)

**Target Variable:**

* `0` → Did not survive
* `1` → Survived

Technologies Used

* Python 
* Pandas & NumPy (Data Handling)
* Matplotlib & Seaborn (Visualization)
* Scikit-learn (Machine Learning)

Steps Performed

1. Data Loading

* Dataset loaded directly using a URL
* Inspected structure using `.head()` and `.info()`

2. Data Cleaning

* Filled missing values:

  * `Age` → Median
  * `Embarked` → Mode
* Removed or handled irrelevant data

3. Data Preprocessing

* Converted categorical data into numerical:

  * `Sex` → Male (0), Female (1)
  * `Embarked` → One-hot encoding

4. Feature Engineering

Created new meaningful features:

* **FamilySize** = SibSp + Parch + 1
* **IsAlone** = 1 (if alone), 0 (otherwise)

These features improved model performance significantly.

5. Feature Selection

Final features used:

* Pclass
* Sex
* Age
* Fare
* FamilySize
* IsAlone
* Embarked

6. Model Building

* Used **Logistic Regression**
* Split data into training and testing sets (80:20)
* Applied feature scaling using StandardScaler

7. Model Evaluation

The model was evaluated using:

* **Accuracy Score**
* **Confusion Matrix**
* **Classification Report**

📊 Data Visualization

The following graphs were used to understand the dataset:

* Survival Count Plot
* Survival based on Gender
* Age Distribution
* Survival based on Passenger Class
* Correlation Heatmap

Key Insights:

* Female passengers had a higher survival rate
* First-class passengers were more likely to survive
* Passengers traveling alone had lower survival chances
* Fare and class showed correlation with survival

Results

* Achieved an accuracy of **~80% to 85%**
* Feature engineering significantly improved performance

Future Improvements

* Try advanced models like Random Forest or Gradient Boosting
* Perform hyperparameter tuning
* Use more feature engineering techniques
* Improve accuracy beyond 90%

Conclusion

This project demonstrates how data preprocessing, feature engineering, and machine learning can be combined to solve a real-world classification problem. Logistic Regression provided a strong baseline model with good accuracy.

Acknowledgment

This project is inspired by the classic Titanic dataset widely used for learning and practicing Machine Learning concepts.


---

⭐ If you like this project, consider giving it a star!
