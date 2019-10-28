In this project, we learn about K Nearest Neighbor (KNN). We build a model of KNN without scaling and with scaling the features first.
The one with scaled features gave better result than the model without scaling as KNN is sensitive to distance.
So, it is good practice to use StandardScaler before building KNN model.

We also learnt how to find best n_neighbors parameter of the model in this project. Finding the best n_neighbors can improve our model performance.

Beside KNN, we created SVC model. We tuned the hyperparameter of SVC model (C and gamma) using GridSearchCV.
The tuning process did increase our model performance.
