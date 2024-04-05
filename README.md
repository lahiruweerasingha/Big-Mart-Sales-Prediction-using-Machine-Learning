# Big Mart Sales Prediction using Machine Learning

This project aims to predict the sales of different items in various outlets of Big Mart using machine learning techniques. The dataset consists of various features such as item weight, item visibility, item type, outlet size, outlet location type, outlet establishment year, etc.

## Dataset obtained from:-
https://www.kaggle.com/datasets/shivan118/big-mart-sales-prediction-datasets/data

## Technical Stack

- Python
- Libraries: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, XGBoost
- Techniques: Machine Learning, Data Preprocessing, Ordinal Encoding, Random Forest Regression, XGBoost Regression, Feature Selection (RFE), Joblib for model saving

## Fundamental Data Science Concepts

This project encompasses several fundamental data science concepts including:

- Data Cleaning: Handling duplicated values, missing values in both numerical and categorical columns, and exploring and manipulating data to prepare it for analysis and modeling.
- Exploratory Data Analysis (EDA): Visualizing distributions, relationships between variables, and understanding the characteristics of the dataset.
- Feature Engineering: Deriving new features from existing ones, such as calculating the age of outlets from establishment year.
- Model Building and Evaluation: Employing Random Forest and XGBoost regression models for sales prediction, evaluating model performance using metrics like Mean Absolute Error (MAE) and R-squared (R2) score.
- Feature Importance: Determining feature importance using XGBoost's feature importances and selecting significant features using Recursive Feature Elimination (RFE).
- Model Deployment: Saving trained models using Joblib for future use in making predictions on unseen data.

## Key Highlights

- Thorough data preprocessing techniques including handling missing values using interpolation and mode imputation, and ordinal encoding for categorical features.
- Detailed exploratory data analysis to understand the distribution of variables and their relationships with the target variable.
- Comparison of Random Forest and XGBoost regression models for predicting sales, with XGBoost showing better performance.
- Feature importance analysis to identify significant features influencing sales prediction.
- Model deployment for predicting sales on unseen data.

