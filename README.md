HOUSING PRICE PREDICTION

This project implements a regression based model to forecast residential property values using the eXtreme Gradient Boosting (XGBoost) algorithm. The model processes 13 key characterstics to determine the prices of houses


KEY FEATURES

Gradient Boosting Framework: Utilizes sequential tree building to iteratively minimize residual errors.

Regularization: Integrates L1 (Lasso) and L2 (Ridge) regularization to prevent overfitting and improve model generalization.

Sparsity Awareness: Features built-in handling for missing data and sparse feature sets, optimizing training efficiency.

Tree Pruning: Employs a depth-first approach to refine decision paths and enhance predictive logic.

IMPLEMENTATION 

Environment: The model is developed in Python Jupyter Notebook in Google Colab using the XGBoost library, Pandas, and Scikit-Learn.

Feature Engineering: It includes data preparation, feature extraction, categorical encoding and statistical analysis of 13 variables to identify primary price drivers.

Optimization: Involves systematic tuning of hyperparameters, L1(lasso) and L2(ridge) regularization to prevent overfitting problem.

Performance: The model is evaluated using mean absolute percent error and normalized RMSE value (adjusted by average).
