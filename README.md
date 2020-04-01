# GRIDSearchCV

# What is grid search?

Grid search is the process of performing hyper parameter tuning in order to determine the optimal values for a given model. To measure the performance of the entire model is based on the hyper parameter values specified.

# Why should I use it?

If you work with ML, you know what a nightmare it is to stipulate values for hyper parameters. There are libraries that have been implemented, such as GridSearchCV of the sklearn library, in order to automate this process and make life a little bit easier for ML enthusiasts.
# How does it work?
1. To import GridSearchCV from the sklearn library.
2. The estimator parameter of GridSearchCV requires the model we are using for the hyper parameter tuning process.
3. The most significant parameters required when working with the rbf kernel of the SVR model are c, gamma and epsilon. A list of values to choose from should be given to each hyper parameter of the model.
