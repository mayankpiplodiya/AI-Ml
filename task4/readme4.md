
Dataset Selection:
A binary classification dataset was used where the target variable had two classes (e.g., 0 and 1).

Preprocessing:
The data was split into training and testing sets. Features were standardized using StandardScaler to improve model performance.

Model Training:
A Logistic Regression model was trained on the scaled training data to classify the target variable.

Evaluation Metrics:
Model performance was evaluated using confusion matrix, precision, recall, F1-score, and ROC-AUC score. The ROC curve was plotted to visualize performance.

Threshold Tuning:
Predicted probabilities were used to tune the classification threshold and observe its effect on precision and recall.

Sigmoid Function:
The sigmoid function was explained and used to convert linear outputs to probabilities, which are essential for classification and threshold tuning.
