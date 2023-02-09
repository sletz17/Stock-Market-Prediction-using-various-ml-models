# Stock-Market-Prediction-using-various-ml-models
Prediction of stock market closing value using machine learning models like Linear Regression, Multiple Regression, KNN, SVM, Random Forest, Decision Tree,
Ride Regression. 

The nifty_close values are predicted using various lag parameters present in the nifty-50 dataset.
The data is split using test_train_split() function in sklearn.The test data is set to 30% of total data while the rest is used to train the models.

The paramter to be predicted is nifty_close and the predictors are lag1,lag2,lag4,lag5.

Appropriate graphs are visualized to depict the relation between actual vs predicted values using matplotlib.
Performance metrics for each model are calculated and displayed.

