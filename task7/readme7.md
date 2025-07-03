
1)Data Loading & Preprocessing-
a. Loaded the breast-cancer.csv dataset and checked for missing values.

b. Encoded the target variable (diagnosis: Benign=0, Malignant=1).

c. Selected two features (radius_mean, texture_mean) for 2D visualization.

d. Normalized features using StandardScaler for optimal SVM performance.

2)Outlier Detection & Removal-
a. Applied Z-score method to detect and remove outliers from the selected features.

b. Created boxplots to visualize outliers before removal.

3)Model Training with SVM-
a. Trained Support Vector Machine (SVM) with both Linear and RBF kernels on cleaned and scaled data.

b. Evaluated models using accuracy on the test set.

4)Decision Boundary Visualization-
Plotted decision boundaries for both kernels using 2D feature space to understand how SVM separates classes.

5)Hyperparameter Tuning-
a. Used GridSearchCV to tune hyperparameters like C and gamma across both kernel types.

b. Identified the best model configuration using 5-fold cross-validation.

6)Model Evaluation-
Performed 5-fold cross-validation on the best model.

Evaluated performance using accuracy, precision, recall, and F1-score via classification report
