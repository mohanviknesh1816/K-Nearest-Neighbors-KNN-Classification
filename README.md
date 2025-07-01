# K-Nearest Neighbors (KNN) Classification
This project demonstrates the application of the K-Nearest Neighbors (KNN) algorithm for classification tasks. The objective is to classify instances into different categories based on numerical input features and to visualize how the KNN model separates classes in a 2D space.
## Train and Evaluate a KNN Classifier
- Trained a `KNeighborsClassifier` using scikit-learn.
- Normalized the input features for better distance-based classification.
- Split the dataset into training and testing subsets.
- Predicted class labels for the test data and evaluated model accuracy.

## Experiment with Different Values of K
- Tested K values ranging from 1 to 10.
- Observed the impact of K on model accuracy.
- Identified the optimal K that provides the highest test accuracy.
## Evaluate with Confusion Matrix
- Generated a confusion matrix for the chosen K value.
- Visualized the matrix using a heatmap-style display.
- Assessed the classification performance across different classes.
## Visualize Decision Boundaries
- Reduced features to two dimensions for visualization.
- Created a mesh grid to simulate new inputs across feature space.
- Plotted decision boundaries showing how the KNN model classifies different regions.
- Overlaid the training samples to show their influence on predictions.
## Results
- The KNN model achieved high accuracy for small values of K (e.g., 3–5).
- As K increased, accuracy slightly decreased, demonstrating model smoothing.
- Decision boundary visualization revealed how KNN partitions feature space based on proximity.
- Confusion matrix showed correct predictions across all classes with very few or no misclassifications.
## Requirements
- Python 3.x  
- scikit-learn  
- pandas  
- matplotlib  
- numpy
