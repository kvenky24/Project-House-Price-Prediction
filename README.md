# House Price Prediction using Machine Learning

## Overview
This project predicts house prices using Machine Learning regression algorithms based on various housing features such as area, quality, location, number of rooms, and construction details.

The project was developed in Jupyter Notebook as part of hands-on practice for Machine Learning and regression analysis.

---

## Problem Statement
Real estate companies and buyers need accurate house price estimation for better decision-making.  
The goal of this project is to build a regression model that predicts house prices based on housing-related features.

---

## Dataset Features

Some important features used in the dataset:

- OverallQual
- GrLivArea
- GarageCars
- TotalBsmtSF
- FullBath
- YearBuilt
- LotArea
- BedroomAbvGr
- KitchenQual
- Neighborhood

Target Variable:
- SalePrice

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Models Used

### 1. Linear Regression
Used as a baseline regression model.

### 2. Decision Tree Regressor
Used to capture non-linear relationships in the dataset.

### 3. Random Forest Regressor
Used for improving prediction performance and reducing overfitting.

---

## Project Workflow

### 1. Data Collection
Loaded training and testing datasets using Pandas.

### 2. Data Cleaning
- Removed unnecessary columns
- Checked dataset structure
- Handled inconsistent values

### 3. Missing Value Handling
- Numerical values filled using mean
- Categorical values filled using mode

### 4. Exploratory Data Analysis (EDA)
Visualized:
- House price distribution
- Correlation between features
- Feature importance
- Relationship between area and price

### 5. Data Preprocessing
- Label Encoding for categorical variables
- Feature selection
- Train-test split

### 6. Model Training
Trained multiple regression models:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

### 7. Model Evaluation
Models were evaluated using:

- R2 Score
- Mean Absolute Error
- Mean Squared Error

R2 Score Formula:

\[
R^2 = 1 - \frac{\sum (y_i-\hat{y}_i)^2}{\sum (y_i-\bar{y})^2}
\]

### 8. Final Prediction
Generated predictions on test dataset and created submission file.

---

## Results

| Model | Performance |
|------|------|
| Linear Regression | Good |
| Decision Tree Regressor | Better |
| Random Forest Regressor | Best |

Random Forest Regressor achieved the best performance in predicting house prices.

---

## Sample Visualizations

The project includes:
- Histograms
- Correlation Heatmaps
- Scatter Plots
- Feature Importance Graphs

---

## Future Improvements

- Hyperparameter tuning
- Feature engineering
- Cross-validation
- XGBoost implementation
- Model deployment using Flask or Streamlit

---

## How to Run the Project

1. Download or clone the repository
2. Open the notebook in Jupyter Notebook
3. Run all cells step by step

---

## Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Regression Analysis
- Feature Engineering
- Data Visualization
- Machine Learning
- Model Evaluation

---

## Author

Venky
