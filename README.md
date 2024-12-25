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
8. [Contributing](#contributing)

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
   git clone https://github.com/Hyscop/Car_Price_Prediction
   cd Car_Price_Prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## **Usage**

1. **Run the Jupyter Notebook**:
   Open the `Car_Price_Predictions.ipynb` file and execute the cells step-by-step to reproduce the results.

2. **Train Models**:

   - The notebook includes code to train Linear Regression, Random Forest, and XGBoost models.
   - Evaluate the models using metrics such as RMSE, MAE, and R² Score.

3. **Visualizations**:
   - Analyze key insights such as feature importance and actual vs. predicted prices.

---

## **Key Features**

- Implements and evaluates multiple machine learning models.
- Identifies influential features affecting car prices.
- Includes hyperparameter tuning for optimal performance.
- Provides a fully documented pipeline from data preprocessing to model evaluation.

---

## **Contributing**

Contributions are welcome! If you would like to improve this project or add new features, feel free to fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.
