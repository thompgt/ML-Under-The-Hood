# ML-Under-The-Hood: Project Workplan 🗺️

This document outlines the step-by-step implementation roadmap for building the `ML-Under-The-Hood` repository.

## 📅 Roadmap

### Phase 1: Project Initialization & Infrastructure ✅
- [x] Initialize Git repository
- [x] Create `.gitignore` and `requirements.txt`
- [x] Draft `README.md` and `WORKPLAN.md`
- [x] Set up project directory structure (`notebooks/`)

### Phase 2: Issue Creation & Tracking ✅
- [x] Create `ISSUES.md` with detailed tasks for each algorithm implementation.

### Phase 3: Sequential Implementation 🚀

#### 1. Linear Regression ✅
#### 2. Logistic Regression ✅
#### 3. K-Nearest Neighbors (KNN) ✅
#### 4. Decision Tree (Basic CART) ✅
#### 5. K-Means Clustering ✅
#### 6. Multi-Layer Perceptron (MLP) ✅

#### 7. Naive Bayes (Gaussian)
- **Focus**: Probability and Bayes' Theorem.
- **Tasks**:
  - Implement `GaussianNB` class.
  - Compute class priors, means, and variances.
  - Calculate Gaussian probability density.

#### 8. Support Vector Machine (Linear SVM)
- **Focus**: Margin maximization and Hinge Loss.
- **Tasks**:
  - Implement `SVM` class.
  - Optimize weights using Gradient Descent on Hinge Loss.
  - Visualize the maximum margin separating hyperplane.

#### 9. Principal Component Analysis (PCA)
- **Focus**: Dimensionality reduction and Eigen decomposition.
- **Tasks**:
  - Implement `PCA` class.
  - Compute covariance matrix, eigenvalues, and eigenvectors.
  - Project data onto principal components.

#### 10. Random Forest
- **Focus**: Ensemble learning and Bootstrap Aggregating (Bagging).
- **Tasks**:
  - Implement `RandomForest` class using our existing `DecisionTree`.
  - Implement bootstrapping and random feature subsets.
  - Aggregate tree predictions via majority voting.

#### 11. AdaBoost
- **Focus**: Boosting and adaptive sample weighting.
- **Tasks**:
  - Implement `AdaBoost` class using decision stumps.
  - Update sample weights iteratively based on errors.
  - Combine weak learners.

#### 12. Ridge Regression
- **Focus**: L2 Regularization.
- **Tasks**:
  - Implement `RidgeRegression` class.
  - Add L2 penalty to the MSE cost function and gradients.
  - Compare coefficients with standard Linear Regression.

#### 13. Lasso Regression
- **Focus**: L1 Regularization and sparsity.
- **Tasks**:
  - Implement `LassoRegression` class.
  - Optimize using Coordinate Descent (since L1 is non-differentiable at 0).
  - Observe coefficient shrinkage to exactly zero.

#### 14. Gaussian Mixture Models (GMM)
- **Focus**: Soft clustering and Expectation-Maximization (EM).
- **Tasks**:
  - Implement `GMM` class.
  - E-Step: Calculate responsibilities.
  - M-Step: Update means, covariances, and mixing weights.

#### 15. DBSCAN
- **Focus**: Density-based clustering.
- **Tasks**:
  - Implement `DBSCAN` class.
  - Identify core points, border points, and noise based on epsilon and min_samples.
  - Expand clusters via neighborhood connectivity.

#### 16. Agglomerative Hierarchical Clustering
- **Focus**: Bottom-up hierarchical clustering.
- **Tasks**:
  - Implement `AgglomerativeClustering` class.
  - Compute distance matrix and repeatedly merge closest clusters.
  - Support single or complete linkage.

---
## 📂 Directory Structure
```text
ML-Under-The-Hood/
├── notebooks/          # Jupyter notebooks for each algorithm
├── .gitignore          # standard Python gitignore
├── README.md           # Project overview and instructions
├── WORKPLAN.md         # This file
├── ISSUES.md           # Mock issue tracker (created in Phase 2)
└── requirements.txt    # Python dependencies
```
