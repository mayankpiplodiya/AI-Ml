
1)Data Loading & Preprocessing-
Loaded the breast-cancer.csv dataset and checked for missing values.
Encoded the target variable (diagnosis: Benign=0, Malignant=1).
Selected two features (radius_mean, texture_mean) for 2D visualization.
Normalized features using StandardScaler for optimal SVM performance.

2)Outlier Detection & Removal-
Applied Z-score method to detect and remove outliers from the selected features.
Created boxplots to visualize outliers before removal.

3)Model Training with SVM-
Trained Support Vector Machine (SVM) with both Linear and RBF kernels on cleaned and scaled data.
Evaluated models using accuracy on the test set.

4)Decision Boundary Visualization-
Plotted decision boundaries for both kernels using 2D feature space to understand how SVM separates classes.

5)Hyperparameter Tuning-
Used GridSearchCV to tune hyperparameters like C and gamma across both kernel types.
Identified the best model configuration using 5-fold cross-validation.

6)Model Evaluation-
Performed 5-fold cross-validation on the best model.
Evaluated performance using accuracy, precision, recall, and F1-score via classification report
