# Forest-Fire-Prediction
The project aims to develop a machine learning model that can accurately predict the burned areas caused by forest fires. Forest fires have become increasingly frequent and devastating disasters, causing significant damage to the environment and posing real emergencies. Traditional methods of detection and response have limitations in terms of speed and accuracy, which can lead to delayed mitigation efforts. Therefore, this project proposes the use of machine learning regression algorithms and ensemble learning techniques to address this challenge.

Various regression algorithms will be implemented, including:
1. Linear Regression: A basic regression model that establishes a linear relationship between the input features and the target variable
2. Lasso and Ridge Regression: These are regularization techniques that help prevent overfitting by adding penalty terms to the regression equation.
3. Support Vector Regression with Radial Basis Function (SVR-rbf): SVR is a powerful regression algorithm that can handle non-linear relationships between variables.
4. Support Vector Regression with Polynomial Kernel (SVR-poly): Similar to SVR-rbf, this variant uses a polynomial kernel for handling non-linear data.

Additionally, ensemble learning will be employed using the Gradient Boosting Regressor. Ensemble methods combine the predictions of multiple models to improve accuracy and robustness.

The project will be implemented in Python, utilizing popular machine learning libraries such as Scikit-Learn and Pandas. Data preprocessing, feature engineering, and model evaluation will be key steps in the workflow. The dataset used for training and testing the models will consist of historical fire data with associated satellite image features.

Data Source: https://archive.ics.uci.edu/ml/datasets/forest+fires

