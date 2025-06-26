
Import and Preprocess the Dataset
Loaded the Housing.csv dataset.
Encoded categorical variables using Label Encoding.
Removed outliers using Z-score.
Plotted boxplots to visualize data distribution.


Split Data into Train-Test Sets
Separated features (X) and target (price).
Split the data into training and testing sets using train_test_split.


Fit a Linear Regression Model
Applied LinearRegression() from sklearn.linear_model to train the model on the training set.


Evaluate the Model
Calculated performance metrics:
MAE (Mean Absolute Error)
MSE (Mean Squared Error)
R² Score (Coefficient of Determination)


Plot Regression Line and Interpret Coefficients
Plotted predicted vs actual prices using the area feature.
Displayed the regression line and its equation:
Price = Intercept + Coefficient × Area.
Printed model coefficients to interpret feature influence on price.
