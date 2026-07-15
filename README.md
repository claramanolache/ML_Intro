# Introduction to Machine Learning

This repository contains my weekly assignments and practice notebooks from an introductory machine learning course. I learned how to prepare data, train different machine learning models, evaluate their performance, and compare their strengths and weaknesses.

## What I Learned

### Week 2 — First Machine Learning Project
- Loaded and explored datasets with Pandas.
- Removed missing values and separated features from the target.
- encoded categorical data and scaled numerical features.
- Split data into training and testing sets.
- Trained and evaluated a linear regression model.

**Main classes and methods:** `OneHotEncoder`, `StandardScaler`, `ColumnTransformer`, `LinearRegression`, `train_test_split()`, `fit()`, `transform()`, `predict()`, `drop()`, and `hist()`.

### Week 3 — Classification
- Created binary and multiclass classifiers.
- Compared a real model with a baseline model.
- Used cross-validation and classification metrics.
- Interpreted precision, recall, F1 score, and confusion matrices.

**Main classes and methods:** `DummyClassifier`, `SGDClassifier`, `cross_val_score()`, `cross_val_predict()`, `precision_score()`, `recall_score()`, `f1_score()`, `confusion_matrix()`, `fit()`, and `predict()`.

### Week 4 — Linear Models
- Compared baseline, linear, and regularized regression models.
- Learned how Ridge, Lasso, and Elastic Net control overfitting.
- Used logistic regression for binary and multiclass classification.
- Learned why feature scaling affects model performance.

**Main classes and methods:** `DummyRegressor`, `LinearRegression`, `Ridge`, `Lasso`, `ElasticNet`, `DummyClassifier`, `LogisticRegression`, `StandardScaler`, `mean_squared_error()`, and `accuracy_score()`.

### Week 5 — Support Vector Machines
- Learned the difference between linear and nonlinear SVMs.
- Explored the regularization parameter `C` and the RBF kernel.
- Used SVMs for both classification and regression.

**Main classes and methods:** `LinearSVC`, `SVC`, `LinearSVR`, `SVR`, `StandardScaler`, `confusion_matrix()`, `mean_squared_error()`, `fit()`, and `predict()`.

### Week 6 — Decision Trees
- Prepared and visualized the penguins dataset.
- Built models to predict penguin species and island.
- Compared SVM and decision-tree classifiers.
- Learned about tree interpretability and regularization.

**Main classes and methods:** `SVC`, `DecisionTreeClassifier`, `plot_tree()`, `StandardScaler`, `train_test_split()`, `dropna()`, `fit()`, `predict()`, and classification metrics.

## Main Libraries

- **NumPy** — numerical operations
- **Pandas** — loading, cleaning, and organizing data
- **Matplotlib and Seaborn** — data visualization
- **scikit-learn** — preprocessing, machine learning models, and evaluation

