# ML-Under-The-Hood: Project Workplan 🗺️

This document outlines the step-by-step implementation roadmap for building the `ML-Under-The-Hood` repository.

## 📅 Roadmap

### Phase 1: Project Initialization & Infrastructure ✅
- [x] Initialize Git repository
- [x] Create `.gitignore` and `requirements.txt`
- [x] Draft `README.md` and `WORKPLAN.md`
- [x] Set up project directory structure (`notebooks/`)

### Phase 2: Issue Creation & Tracking 🛠️
- [ ] Create `ISSUES.md` with detailed tasks for each algorithm implementation.

### Phase 3: Sequential Implementation 🚀

#### 1. Linear Regression
- **Focus**: Gradient Descent and the Normal Equation.
- **Tasks**:
  - Implement `LinearRegression` class.
  - Compute Mean Squared Error (MSE) loss.
  - Visualize regression line and cost history.

#### 2. Logistic Regression
- **Focus**: Binary classification and the Sigmoid function.
- **Tasks**:
  - Implement `LogisticRegression` class.
  - Use Binary Cross-Entropy loss.
  - Visualize decision boundaries.

#### 3. K-Nearest Neighbors (KNN)
- **Focus**: Distance-based classification.
- **Tasks**:
  - Implement `KNN` class.
  - Support multiple distance metrics (Euclidean, Manhattan).
  - Visualize neighbors and decision regions.

#### 4. Decision Tree (Basic CART)
- **Focus**: Recursive partitioning using Gini impurity.
- **Tasks**:
  - Implement `DecisionTree` class.
  - Handle split logic for classification.
  - Visualize tree structure or decision boundaries.

#### 5. K-Means Clustering
- **Focus**: Unsupervised grouping and centroids.
- **Tasks**:
  - Implement `KMeans` class.
  - Update centroids iteratively.
  - Visualize cluster assignments and centroid movement.

#### 6. Multi-Layer Perceptron (MLP)
- **Focus**: Feed-forward networks and Backpropagation.
- **Tasks**:
  - Implement `MLP` class (1 hidden layer).
  - Compute ReLU/Sigmoid activations.
  - Train on a simple XOR or non-linear dataset.

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
