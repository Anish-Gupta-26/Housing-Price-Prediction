HOUSING PRICE PREDICTION

This project implements a regression based model to forecast residential property values using the eXtreme Gradient Boosting (XGBoost) algorithm. The model processes 13 key characterstics to determine the prices of houses


KEY FEATURES

Gradient Boosting Framework: Utilizes sequential tree building to iteratively minimize residual errors.

Regularization: Integrates L1 (Lasso) and L2 (Ridge) regularization to prevent overfitting and improve model generalization.

Sparsity Awareness: Features built-in handling for missing data and sparse feature sets, optimizing training efficiency.

Tree Pruning: Employs a depth-first approach to refine decision paths and enhance predictive logic.

IMPLEMENTATION 

Environment: Developed in Python using the XGBoost library, Pandas, and Scikit-Learn.

Feature Engineering: Includes categorical encoding and statistical analysis of 13 variables to identify primary price drivers.

Optimization: Involves systematic tuning of hyperparameters, specifically learning rates and maximum tree depth, to ensure model stability
