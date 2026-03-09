# House Price Prediction using Linear Regression

## Project Overview

This project implements a **Linear Regression model** to predict house prices based on important features such as **square footage, number of bedrooms, and number of bathrooms**.
The project also includes **data analysis and visualization** to understand the relationships between house features and prices.

## Dataset

The dataset used in this project is **house_price_regression_dataset.csv**.

### Features Used

* Square_Footage
* Num_Bedrooms
* Num_Bathrooms

### Target Variable

* House_Price

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib

## Project Steps

1. Import required libraries
2. Load the dataset
3. Analyze the dataset
4. Visualize relationships between features and house prices
5. Select features and target variable
6. Train a Linear Regression model
7. Predict house prices
8. Evaluate the model

## Data Visualization

The following visualizations are used in the project:

* Square Footage vs House Price (Scatter Plot)
* Bedrooms vs House Price
* Bathrooms vs House Price
* House Price Distribution (Histogram)
* Correlation Heatmap

## How to Run the Project

1. Clone the repository
2. Install required libraries

```
pip install pandas matplotlib scikit-learn
```

3. Place the dataset file in the project folder:

```
house_price_regression_dataset.csv
```

4. Run the Python programs in VS Code or Jupyter Notebook.

## Example Prediction

The trained model can predict the price of a house using input features such as:

* Square Footage
* Number of Bedrooms
* Number of Bathrooms

Example:

```
prediction = model.predict([[2000,3,2]])
```

## Conclusion

The Linear Regression model helps estimate house prices based on property features.
Visualization techniques help understand the relationship between house size, number of rooms, and price.

