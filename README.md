# Product Demand Prediction

## Documentation
### Problem Statement
The problem at hand involves predicting the number of units sold based on the total price and base price of a product. The dataset used for this task is loaded from a CSV file, and different regression models are employed to make predictions.

### Data Description
The dataset contains the following columns:

-'ID': Identifier for each data point.
-'Total Price': The total price of the product.
-'Base Price': The base price of the product.
-'Units Sold': The number of units sold, which is the target variable.
Approach

### Data Preprocessing

-The dataset is loaded from the CSV file using Pandas.
-Missing values in the 'Total Price' column are handled by filling them with the mean value.
-The 'Total Price' and 'Base Price' columns are rounded to two decimal places for consistency.
Modeling

The data is split into training and testing sets.
Four regression models are trained:
-Linear Regression
-Decision Tree Regressor
-Random Forest Regressor
-XGBoost Regressor
### Model Evaluation

-The models' performance is evaluated using Root Mean Squared Error (RMSE) and R-squared.
-RMSE measures the average deviation of predictions from actual values, and R-squared quantifies the model's goodness of fit.
### Visualization

-The predictions of each model are visualized to compare their performance.
### Solution
The code provided in the .ipynb file walks through the entire process, from data loading to model training and evaluation. The models considered include Linear Regression, Decision Tree, Random Forest, and XGBoost. Their performance metrics are computed and compared visually.

### Results
From the analysis, it is observed that the Random Forest and Decision Tree models outperform the other