# kaggle_housing
https://www.kaggle.com/c/house-prices-advanced-regression-techniques - A classic machine learning dataset for regression machine learning techniques to explore.


# House Price Prediction
Starting with feature engineering and removing redundant columns, the data is then scaled and then encoded (ordinally or one-hot). Various classic machine 
learning techniques are then applied to predict the SalePrice of houses, including:
* Multiple Linear Regression - Normal + regularized methods (Lasso, Ridge, Elastic net & Huber)
* Deep Neural Network - Simple feed forward style with relu activation functions, early stopping on validation data and use of Huber loss
* Ensemble Methods - Random Forest and Adaboost
* Knn & SVM - Not really suitable for regression prediction and it shows, but is still included

The performance of each method is then explored on the separeted test dataset, concluding with the ensemble methods having the best performance (with Adaboost slightly edging it).
