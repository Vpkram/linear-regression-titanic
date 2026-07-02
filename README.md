# Task 3: Linear Regression

## Objective
Implement and understand simple & multiple linear 
regression on Titanic Dataset.

## Dataset
Titanic Dataset from Kaggle

## Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- NumPy

## Steps Performed
1. Imported and preprocessed the dataset
2. Split data into train (80%) and test (20%) sets
3. Fitted Linear Regression model using sklearn
4. Evaluated model using MAE, MSE, RMSE and R²
5. Plotted Actual vs Predicted Fare
6. Interpreted model coefficients

## Model Performance
- MAE  → $20.81
- RMSE → $30.47
- R²   → 0.40 (model explains 40% of fare variation)

## Key Findings
- Pclass is the strongest predictor of Fare (-33.93)
- Embarked port significantly affects fare price
- Age has almost no effect on fare (-0.08)
- Family size (Parch, SibSp) slightly increases fare
