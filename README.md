#House Price Prediction (Kaggle)

This project predicts house prices using the Kaggle House Prices dataset. It includes data preprocessing, feature engineering, and training multiple regression models.

**What I did**

1. Loaded train and test datasets
2. Merged both for consistent preprocessing
3. Visualized missing values using heatmaps
4. Removed categorical columns with excessive missing data
5. Filled remaining null values (mode for discrete, mean for continuous)
6. Applied one-hot encoding to categorical features
7. Combined numerical and encoded features
8. Split data into training and validation sets
9. Trained and compared:Linear Regression,XGBoost RegressorRandom Forest Regressor
10. Evaluated models using Mean Squared Error
11. Generated predictions for Kaggle test data
Saved final predictions to output.csv

#Libraries Used
Pandas
NumPy
Seaborn
Scikit-learn
XGBoost
 
 #Goal:
To learn the complete machine learning pipeline including data cleaning, encoding, regression modeling, and evaluation.
