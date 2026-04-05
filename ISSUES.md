# Project Issues 🛠️

This file tracks the implementation progress of each algorithm as "mock" issues.

---

## [Issue #1] Implement Linear Regression from scratch 📈
- [x] **Core Logic**: Write `LinearRegression` class with `fit()` and `predict()` methods.
- [x] **Optimization**: Support both Gradient Descent and the Normal Equation.
- [x] **Toy Dataset**: Generate simple linear data with noise.
- [x] **Evaluation**: Track and plot the Mean Squared Error (MSE) loss history.
- [x] **Visualization**: Plot the resulting regression line against the data points.

---

## [Issue #2] Implement Logistic Regression from scratch 🧬
- [x] **Core Logic**: Implement the Sigmoid activation and `LogisticRegression` class.
- [x] **Loss Function**: Implement Binary Cross-Entropy (Log Loss).
- [x] **Optimization**: Update weights using Gradient Descent.
- [x] **Toy Dataset**: Generate linearly separable data points.
- [x] **Visualization**: Plot the decision boundary and the Sigmoid probability curve.

---

## [Issue #3] Implement K-Nearest Neighbors (KNN) from scratch 📍
- [x] **Core Logic**: Implement the KNN algorithm (no training phase, just distance calculation).
- [x] **Distance Metrics**: Support Euclidean and Manhattan distances.
- [x] **Toy Dataset**: Generate multiple clusters of data.
- [x] **Visualization**: Plot the decision regions using a color-coded grid.

---

## [Issue #4] Implement Decision Tree (CART) from scratch 🌳
- [x] **Core Logic**: Implement recursive splitting and the `DecisionTree` class.
- [x] **Impurity Metric**: Implement Gini Impurity calculation.
- [x] **Splitting**: Find the best feature and threshold to split the data.
- [x] **Toy Dataset**: Create a non-linear classification dataset.
- [x] **Visualization**: Visualize the resulting decision boundaries.

---

## [Issue #5] Implement K-Means Clustering from scratch 🎯
- [x] **Core Logic**: Implement the `KMeans` class with centroid initialization.
- [x] **Clustering**: Implement the E-M (Expectation-Maximization) loop.
- [x] **Inertia**: Track the sum of squared distances to the nearest centroid.
- [x] **Toy Dataset**: Generate unlabelled blobs of data.
- [x] **Visualization**: Animate or plot the centroids moving through iterations.

---

## [Issue #6] Implement Multi-Layer Perceptron (MLP) from scratch 🧠
- [x] **Core Logic**: Implement a basic neural network with one hidden layer.
- [x] **Activations**: Implement ReLU and Sigmoid/Softmax activation functions.
- [x] **Backpropagation**: Compute gradients and update weights.
- [x] **Toy Dataset**: Use a non-linearly separable dataset (e.g., XOR problem or Moons).
- [x] **Visualization**: Plot the decision boundary and training loss over time.

---

## [Issue #7] Implement Naive Bayes from scratch 📊
- [x] **Core Logic**: Implement `GaussianNB` class.
- [x] **Statistics**: Compute per-class mean, variance, and prior probabilities.
- [x] **Prediction**: Calculate posterior probabilities using Gaussian PDF.
- [x] **Toy Dataset**: Generate a classification dataset.
- [x] **Visualization**: Plot the decision boundary.

---

## [Issue #8] Implement Support Vector Machine (SVM) from scratch ⚔️
- [x] **Core Logic**: Implement linear `SVM` class.
- [x] **Loss Function**: Implement Hinge Loss with L2 regularization.
- [x] **Optimization**: Use Gradient Descent to update weights and bias.
- [x] **Toy Dataset**: Generate linearly separable data points.
- [x] **Visualization**: Plot the decision boundary and the margins.

---

## [Issue #9] Implement Principal Component Analysis (PCA) from scratch 📉
- [x] **Core Logic**: Implement `PCA` class for dimensionality reduction.
- [x] **Math**: Compute the covariance matrix.
- [x] **Math**: Perform Eigen decomposition to find principal components.
- [x] **Toy Dataset**: Generate a high-dimensional dataset or highly correlated 2D data.
- [x] **Visualization**: Plot the original data with principal component vectors, and the projected data.

---

## [Issue #10] Implement Random Forest from scratch 🌲🌲🌲
- [x] **Core Logic**: Implement `RandomForest` using multiple `DecisionTree` instances.
- [x] **Bagging**: Implement bootstrap sampling of the dataset.
- [x] **Feature Selection**: Implement random subset feature selection at each split.
- [x] **Toy Dataset**: Generate a complex non-linear classification dataset.
- [x] **Visualization**: Plot the Random Forest decision boundary.

---

## [Issue #11] Implement AdaBoost from scratch 🚀
- [x] **Core Logic**: Implement `AdaBoost` class using decision stumps (depth=1 trees).
- [x] **Weighting**: Update sample weights based on misclassification errors.
- [x] **Ensemble**: Compute alpha (amount of say) for each stump and aggregate.
- [x] **Toy Dataset**: Generate a challenging classification dataset.
- [x] **Visualization**: Plot the ensemble decision boundary.

---

## [Issue #12] Implement Ridge Regression from scratch 📏
- [x] **Core Logic**: Implement `RidgeRegression` class inheriting or mimicking Linear Regression.
- [x] **Regularization**: Add L2 penalty term to the cost function.
- [x] **Optimization**: Compute gradients including the L2 derivative.
- [x] **Toy Dataset**: Generate regression data with multicollinearity or high noise.
- [x] **Visualization**: Plot the regression line and compare coefficient magnitudes with standard LR.

---

## [Issue #13] Implement Lasso Regression from scratch 🎯
- [x] **Core Logic**: Implement `LassoRegression` class.
- [x] **Optimization**: Implement Coordinate Descent to handle the non-differentiable L1 penalty.
- [x] **Sparsity**: Observe coefficients being shrunk exactly to zero.
- [x] **Toy Dataset**: Generate regression data with many irrelevant features.
- [x] **Visualization**: Plot the regression line and display the resulting sparse weights.

---

## [Issue #14] Implement Gaussian Mixture Models (GMM) from scratch ☁️
- [x] **Core Logic**: Implement `GMM` class.
- [x] **E-Step**: Calculate responsibilities (probabilities of each point belonging to each cluster).
- [x] **M-Step**: Update cluster means, covariances, and mixing weights.
- [x] **Toy Dataset**: Generate blobs with elliptical shapes.
- [x] **Visualization**: Plot the data with contours of the Gaussian distributions.

---

## [Issue #15] Implement DBSCAN from scratch 🔍
- [x] **Core Logic**: Implement `DBSCAN` class.
- [x] **Neighborhoods**: Find neighbors for each point within radius epsilon.
- [x] **Clustering**: Identify core points and expand clusters, labeling noise.
- [x] **Toy Dataset**: Generate non-spherical clusters (e.g., moons or circles).
- [x] **Visualization**: Plot the clusters, highlighting core points and noise points.

---

## [Issue #16] Implement Agglomerative Hierarchical Clustering from scratch 🏢
- [x] **Core Logic**: Implement `AgglomerativeClustering` class.
- [x] **Distance Matrix**: Compute pairwise distances between all clusters.
- [x] **Merging**: Iteratively merge the two closest clusters until $K$ clusters remain.
- [x] **Toy Dataset**: Generate a multi-cluster dataset.
- [x] **Visualization**: Plot the resulting clusters (and optionally a dendrogram if simple enough).

---
