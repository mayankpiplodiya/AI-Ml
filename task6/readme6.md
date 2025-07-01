KNN Classifier on Iris Dataset

1)Imported and preprocessed the Iris dataset by removing the unnecessary Id column and separating features (X) and target (y).

2)Normalized the features using MinMaxScaler to ensure fair distance calculations for KNN.

3)Split the dataset into training and testing sets using an 70/30 ratio for model evaluation.

4)Trained K-Nearest Neighbors classifiers for different values of K (from 1 to 10) using KNeighborsClassifier.

5)Evaluated model performance using accuracy scores and printed results for each K to analyze performance trends.

6)Plotted Accuracy vs K graph to visualize how the choice of K impacts test accuracy and to help choose the optimal K value.
