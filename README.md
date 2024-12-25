# Save the README content into a markdown file

readme_content = """

# **Car Price Prediction**

This project leverages machine learning techniques to predict car prices based on key attributes such as engine size, curb weight, and horsepower. By analyzing a dataset of car specifications, the project identifies the most influential features affecting car prices and provides accurate predictions using the best-performing machine learning models.

---

## **Table of Contents**

1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Models and Methods](#models-and-methods)
4. [Results](#results)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Key Features](#key-features)
8. [Visualizations](#visualizations)
9. [Contributing](#contributing)

---

## **Overview**

The primary goal of this project is to predict car prices based on various features using machine learning. Three models were evaluated—Linear Regression, Random Forest, and XGBoost—to determine the most accurate and reliable model for price prediction. The Random Forest model demonstrated the best performance and was further optimized using hyperparameter tuning.

---

## **Dataset**

- **Source**: The dataset is obtained from Kaggle ([Car Price Prediction Dataset](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction/data)).
- **Description**: The dataset contains specifications for various car models, including:
  - Engine size
  - Horsepower
  - Fuel type
  - Curb weight
  - Number of cylinders
  - Highway MPG
  - Price (Target variable)

---

## **Models and Methods**

1. **Exploratory Data Analysis (EDA)**:

   - Distribution of car prices.
   - Correlation analysis of numerical features.
   - Visualizations of influential features.

2. **Data Preprocessing**:

   - Handled missing values.
   - Categorical encoding using `LabelEncoder`.
   - Feature scaling using `StandardScaler`.

3. **Machine Learning Models**:

   - Linear Regression
   - Random Forest Regressor
   - XGBoost Regressor

4. **Hyperparameter Tuning**:
   - Used `GridSearchCV` to optimize Random Forest hyperparameters.

---

## **Results**

- **Best Model**: Random Forest Regressor
- **Evaluation Metrics**:
  - **Root Mean Squared Error (RMSE)**: 1855.76
  - **Mean Absolute Error (MAE)**: 1297.17
  - **R² Score**: 0.96
- **Feature Importance**:
  - Engine Size, Curb Weight, and Horsepower were the most influential features.

---

## **Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/Hyscop/Car_Price_Prediction.git
   cd Car_Price_Prediction
   ```
