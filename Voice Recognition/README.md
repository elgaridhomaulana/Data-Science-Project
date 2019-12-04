Create XGBClassifier model to predict whether the data is a female or male voice.
Learning curve was plotted to know what is the best train size to use for fit the model.
I also use pipeline to do StandardScaler and PCA to preprocessing the features.
Hyperparameters of XGBClassifier (learning_rate, max_depth, n_estimators) were found by using GridSearchCV