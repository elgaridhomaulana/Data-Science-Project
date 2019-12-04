The purpose of this project is to predict whether a patient has diabetes or not by using several medical indicators as the features.

The features are:
Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeF, and Age
The target is 'Outcome' column in the dataset

Since this is classification problem, I use model for classification. The models that I used for predicting are:
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. K Nearest Neighbour
5. Gradient Boosting
6. Support Vector Machine

The model that gave me best result are Logistic Regression and Random Forest.
I tried to Standardize the feature before predicting, and it gave me slightly better result.
Hyperparameter tuning using RandomizedSearchCV in my case didn't work quite well. Maybe better approach of hyperparameters tuning, like GridSearchCV is needed.