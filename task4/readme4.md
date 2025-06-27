Dataset Selection:
 A binary classification dataset was used where the target variable had two distinct classes (e.g., 0 and 1).

Preprocessing:
 Performed necessary preprocessing including handling missing values and removing outliers using Z-score method to clean the dataset.

Feature Scaling and Split:
 The dataset was split into training and testing sets, and features were standardized using StandardScaler for better model performance.

Model Training:
 A Logistic Regression model was trained on the processed and scaled training data to classify the binary target.

Evaluation Metrics:
 Model performance was evaluated using confusion matrix, precision, recall, F1-score, ROC-AUC score, and ROC curve visualization.

Threshold Tuning and Sigmoid Explanation:
 Used predicted probabilities to manually tune classification thresholds. Explained the sigmoid function used to convert model outputs into class probabilitie
