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
- [ ] **Core Logic**: Implement `GaussianNB` class.
- [ ] **Statistics**: Compute per-class mean, variance, and prior probabilities.
- [ ] **Prediction**: Calculate posterior probabilities using Gaussian PDF.
- [ ] **Toy Dataset**: Generate a classification dataset.
- [ ] **Visualization**: Plot the decision boundary.

---

## [Issue #8] Implement Support Vector Machine (SVM) from scratch ⚔️
- [ ] **Core Logic**: Implement linear `SVM` class.
- [ ] **Loss Function**: Implement Hinge Loss with L2 regularization.
- [ ] **Optimization**: Use Gradient Descent to update weights and bias.
- [ ] **Toy Dataset**: Generate linearly separable data points.
- [ ] **Visualization**: Plot the decision boundary and the margins.

---

## [Issue #9] Implement Principal Component Analysis (PCA) from scratch 📉
- [ ] **Core Logic**: Implement `PCA` class for dimensionality reduction.
- [ ] **Math**: Compute the covariance matrix.
- [ ] **Math**: Perform Eigen decomposition to find principal components.
- [ ] **Toy Dataset**: Generate a high-dimensional dataset or highly correlated 2D data.
- [ ] **Visualization**: Plot the original data with principal component vectors, and the projected data.

---

## [Issue #10] Implement Random Forest from scratch 🌲🌲🌲
- [ ] **Core Logic**: Implement `RandomForest` using multiple `DecisionTree` instances.
- [ ] **Bagging**: Implement bootstrap sampling of the dataset.
- [ ] **Feature Selection**: Implement random subset feature selection at each split.
- [ ] **Toy Dataset**: Generate a complex non-linear classification dataset.
- [ ] **Visualization**: Plot the Random Forest decision boundary.

---

## [Issue #11] Implement AdaBoost from scratch 🚀
- [ ] **Core Logic**: Implement `AdaBoost` class using decision stumps (depth=1 trees).
- [ ] **Weighting**: Update sample weights based on misclassification errors.
- [ ] **Ensemble**: Compute alpha (amount of say) for each stump and aggregate.
- [ ] **Toy Dataset**: Generate a challenging classification dataset.
- [ ] **Visualization**: Plot the ensemble decision boundary.

---

## [Issue #12] Implement Ridge Regression from scratch 📏
- [ ] **Core Logic**: Implement `RidgeRegression` class inheriting or mimicking Linear Regression.
- [ ] **Regularization**: Add L2 penalty term to the cost function.
- [ ] **Optimization**: Compute gradients including the L2 derivative.
- [ ] **Toy Dataset**: Generate regression data with multicollinearity or high noise.
- [ ] **Visualization**: Plot the regression line and compare coefficient magnitudes with standard LR.

---

## [Issue #13] Implement Lasso Regression from scratch 🎯
- [ ] **Core Logic**: Implement `LassoRegression` class.
- [ ] **Optimization**: Implement Coordinate Descent to handle the non-differentiable L1 penalty.
- [ ] **Sparsity**: Observe coefficients being shrunk exactly to zero.
- [ ] **Toy Dataset**: Generate regression data with many irrelevant features.
- [ ] **Visualization**: Plot the regression line and display the resulting sparse weights.

---

## [Issue #14] Implement Gaussian Mixture Models (GMM) from scratch ☁️
- [ ] **Core Logic**: Implement `GMM` class.
- [ ] **E-Step**: Calculate responsibilities (probabilities of each point belonging to each cluster).
- [ ] **M-Step**: Update cluster means, covariances, and mixing weights.
- [ ] **Toy Dataset**: Generate blobs with elliptical shapes.
- [ ] **Visualization**: Plot the data with contours of the Gaussian distributions.

---

## [Issue #15] Implement DBSCAN from scratch 🔍
- [ ] **Core Logic**: Implement `DBSCAN` class.
- [ ] **Neighborhoods**: Find neighbors for each point within radius epsilon.
- [ ] **Clustering**: Identify core points and expand clusters, labeling noise.
- [ ] **Toy Dataset**: Generate non-spherical clusters (e.g., moons or circles).
- [ ] **Visualization**: Plot the clusters, highlighting core points and noise points.

---

## [Issue #16] Implement Agglomerative Hierarchical Clustering from scratch 🏢
- [ ] **Core Logic**: Implement `AgglomerativeClustering` class.
- [ ] **Distance Matrix**: Compute pairwise distances between all clusters.
- [ ] **Merging**: Iteratively merge the two closest clusters until $K$ clusters remain.
- [ ] **Toy Dataset**: Generate a multi-cluster dataset.
- [ ] **Visualization**: Plot the resulting clusters (and optionally a dendrogram if simple enough).

---
