# Boston Housing Price Prediction

This is a simple Python project that predicts the **price of a house** in the Boston area using the **Boston Housing dataset**. The program asks the user to enter **5 main details** about the house and predicts the price in **US Dollars ($)**.

---

## Features

- Predicts house prices using **Random Forest Regressor**.  
- Interactive input for 5 important features:
  - RM: Average number of rooms per dwelling  
  - LSTAT: % lower status of the population  
  - PTRATIO: Pupil-teacher ratio by town  
  - CRIM: Per capita crime rate by town  
  - DIS: Weighted distances to employment centers  
- Input validation with suggested ranges.  
- Displays predicted price in **USD**.  
- Shows model performance (MAE & RMSE).  

---

## Requirements

- Python 3.x  
- Libraries:
  - pandas  
  - numpy  
  - scikit-learn  

Enter values for the 5 features when prompted. Example:
RM: 6.0
LSTAT: 5.0
PTRATIO: 15
CRIM: 0.1
DIS: 6.0

The program will show something like:
Predicted House Price: $16,060.00
Note: The predicted price is in US Dollars based on the Boston Housing dataset (values in $1000s).

