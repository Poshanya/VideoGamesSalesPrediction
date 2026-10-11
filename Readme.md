# Video Game Sales Prediction

## Project Overview

This project uses machine learning to analyze video game sales data and predict sales using features from historical video game records. It explores data preprocessing, feature engineering, model training, and model evaluation.

## Objectives

- Analyze historical video game sales data.
- Clean and preprocess the dataset.
- Explore relationships between game attributes and sales.
- Train and compare multiple regression models.
- Evaluate model performance using appropriate metrics.

## Tech Stack

- **Language:** Python
- **Data Analysis:** Pandas
- **Machine Learning:** Scikit-learn, XGBoost
- **Techniques:** Data Cleaning, Feature Engineering, Cross-Validation, Hyperparameter Tuning

## Dataset and Preprocessing

The project started with a dataset containing 16,720 video game records. Preprocessing included handling missing values, encoding categorical variables, feature engineering, and cleaning the data. The processed dataset contained 4,845 records.

## Models Implemented

The following regression models were evaluated:

- Linear Regression
- K-Nearest Neighbors (KNN)
- Support Vector Regression (SVR)
- Random Forest Regressor
- XGBoost Regressor

GridSearchCV, 5-fold cross-validation, and hyperparameter tuning were used during model evaluation.

## Results

The best reported model evaluation achieved an **R² score of 0.653**.

This indicates that the evaluated model explained approximately 65.3% of the variance in the target variable on the evaluation data. Results may vary depending on the train/test split and evaluation procedure.

## Key Learnings

- Preparing real-world datasets for analysis.
- Handling missing values and categorical features.
- Performing feature engineering.
- Comparing regression models.
- Applying cross-validation and hyperparameter tuning.

## How to Run

1. Clone this repository.
2. Install the required Python libraries.
3. Open the project notebook or Python script.
4. Run the preprocessing, model training, and evaluation steps.

Install the core dependencies with:

```bash
pip install pandas scikit-learn xgboost jupyter
```

## Author

**Maddula Poshanya Guptha**

- [GitHub](https://github.com/Poshanya)
- [LinkedIn](https://www.linkedin.com/in/poshanya-guptha-maddula/)
- [LeetCode](https://leetcode.com/u/M_Poshanya_Guptha/)
