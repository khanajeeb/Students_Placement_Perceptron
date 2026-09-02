# Students Placement Perceptron

Student placement prediction using Perceptron and Polynomial Features.

##  Project Overview
This project demonstrates how to solve the limitations of a vanilla Perceptron Classifier when dealing with overlapping, non-linearly separable data. By using **Polynomial Features** within a Scikit-Learn pipeline, the model's accuracy was successfully boosted.

##  Steps Performed:
1. **Data Exploration:** Checked the data structure using `head()`, `info()`, and `describe()`.
2. **Data Visualization:** Created scatter plots using `seaborn` to check the feature distribution (`cgpa` vs `resume_score`).
3. **Pipeline Building:** Setup a Scikit-Learn pipeline using `make_pipeline` with `StandardScaler` and `PolynomialFeatures(degree=2)`.
4. **Model Training:** Trained the `Perceptron` model with an `elasticnet` penalty to prevent overfitting.

##  Final Results:
# **Training Accuracy:** 97.5%
# **Testing Accuracy:** 95.0%
# The model successfully managed to separate the overlapping classes using a curved decision boundary, minimizing errors down to just 1 False Negative.

