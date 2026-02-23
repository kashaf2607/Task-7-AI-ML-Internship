# Task-7-AI-ML

# Support Vector Machine (SVM) – Binary Classification

## Objective

The objective of this project is to implement Support Vector Machine (SVM) for binary classification and evaluate its performance using different kernels and hyperparameter tuning.

## Steps Performed

### 1. Dataset Loading and Preparation

* Loaded the dataset for binary classification.
* Handled missing values (if any).
* Encoded categorical variables (if required).
* Split the dataset into training and testing sets.
* Scaled features using standardization to improve SVM performance.

### 2. Training SVM Models

* Trained an SVM model using:

  * **Linear Kernel**
  * **RBF (Radial Basis Function) Kernel**
* Compared performance between both kernels.

### 3. Decision Boundary Visualization

* Used 2D feature data (or reduced dimensions) to visualize the decision boundary.
* Plotted support vectors and margins to understand model behavior.

### 4. Hyperparameter Tuning

* Tuned important SVM parameters:

  * **C (Regularization parameter)**
  * **gamma (for RBF kernel)**
* Tested multiple values to improve model accuracy.

### 5. Cross-Validation

* Applied cross-validation to evaluate model performance.
* Ensured model generalization and reduced overfitting.

## Evaluation Metrics

* Accuracy Score
* Cross-validation Score

## Conclusion

The project demonstrates how SVM works for binary classification using different kernels. Hyperparameter tuning and cross-validation significantly improve model performance and help select the best model.
