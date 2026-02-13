House Price Prediction (Kaggle)

This project predicts house prices using the Kaggle House Prices dataset. It includes data preprocessing, feature engineering, and training multiple regression models.

What I did

Loaded train and test datasets
Merged both for consistent preprocessing
Visualized missing values using heatmaps
Removed categorical columns with excessive missing data
Filled remaining null values (mode for discrete, mean for continuous)
Applied one-hot encoding to categorical features
Combined numerical and encoded features
Split data into training and validation sets
Trained and compared:Linear Regression,XGBoost RegressorRandom Forest Regressor
Evaluated models using Mean Squared Error
Generated predictions for Kaggle test data
Saved final predictions to output.csv

Libraries Used
Pandas
NumPy
Seaborn
Scikit-learn
XGBoost
 
 Goal:
To learn the complete machine learning pipeline including data cleaning, encoding, regression modeling, and evaluation.
