## 📖 Coursework Description & Overview

This repository serves as a comprehensive archive of practical coursework, laboratory assignments, and applied machine learning projects completed as part of the academic curriculum for **[Course Code]: [Course Name]** at **[University/College Name]**.

The primary objective of this coursework is to bridge theoretical statistical foundations with hands-on computational implementations, moving from mathematical derivation to production-ready code.

---

### 🎯 Core Focus Areas & Pedagogical Progression

The implementations documented across these assignments follow a dual-track pedagogical methodology:

1. **Foundational & First-Principles Implementation:**
Before leveraging modern abstraction libraries, foundational algorithms (such as Ordinary Least Squares, Batch/Stochastic Gradient Descent, Logistic Regression, $k$-Nearest Neighbors, and Single/Multi-Layer Perceptrons) are implemented from scratch using **NumPy**. This establishes a granular understanding of vectorized operations, loss functions, optimization surfaces, numerical stability, and matrix calculus.
2. **Standardized Industrial Workflows:**
Building on low-level implementations, complex workflows are constructed using modern data science frameworks such as **Scikit-Learn**, **Pandas**, and **SciPy**. This track emphasizes industry best practices: modular transformation pipelines, data leakage prevention, cross-validation strategies, and hyperparameter optimization.

---

### 🔬 The Machine Learning Lifecycle Covered

Each assignment repository directory encapsulates an end-to-end machine learning pipeline:

* **Exploratory Data Analysis (EDA):** Statistical profiling, distribution analysis, correlation matrices, and multivariate data visualization using Matplotlib and Seaborn to identify skewness, collinearity, and anomalies.
* **Data Preprocessing & Feature Engineering:** Robust imputation strategies for missing data, categorical encoding (One-Hot, Ordinal, Target Encoding), normalization/standardization scaling techniques, dimensionality reduction via Principal Component Analysis (PCA), and feature selection.
* **Model Development & Exploration:**
* *Supervised Learning:* Linear, Ridge ($L_2$), Lasso ($L_1$), and ElasticNet Regression; Logistic Regression, Support Vector Machines (SVM) with linear and non-linear kernels (RBF, Polynomial), Decision Trees, and Ensemble Methods (Random Forest, Gradient Boosting, XGBoost).
* *Unsupervised Learning:* Centroid-based clustering ($K$-Means), density-based clustering (DBSCAN), hierarchical clustering (Agglomerative), and dimensionality reduction algorithms.
* *Neural Networks & Deep Learning Foundations:* Feedforward Artificial Neural Networks (ANNs), activation function dynamics (ReLU, Sigmoid, Softmax), forward propagation, backpropagation derivations, and regularization methods (Dropout, Weight Decay).


* **Validation & Metric Evaluation:** Thorough performance auditing using task-specific metrics—Precision, Recall, $F_1$-Score, ROC-AUC, Log-Loss, and Confusion Matrices for classification; MSE, RMSE, MAE, and $R^2$ score for regression.
* **Hyperparameter Optimization:** Systematic parameter tuning utilizing `GridSearchCV` and `RandomizedSearchCV` paired with stratified $k$-fold cross-validation.

---

### 🛠️ Key Learning Outcomes

* **Mathematical Grounding:** Gained practical intuition for loss landscape optimization, the bias-variance tradeoff, and mathematical assumptions behind both parametric and non-parametric algorithms.
* **Code Reproducibility & Clean Architecture:** Maintained documented, reproducible Jupyter Notebooks alongside modular, reusable Python scripts (`.py`) following PEP 8 style standards.
* **Analytical Reporting:** Accompanied implementations with analytical write-ups interpreting error rates, diagnostic residual plots, and performance trade-offs across distinct algorithmic baselines.
