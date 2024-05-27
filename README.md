# German second hand car price prediction using following methods:

### 1-Summary

In this project six different models are used to predict the price of second hand cars based on the following selected features: year, power per kw, mileage in km and brand. In order to do this, the following models are used: Linear Regression, Decision Tree, Bagging, AdaBoost, K-Nearest Neighbours and Random Forest.  A variety of models is chosen, ranging from linear regression as a classical linear method to nonlinear methods such as decision tree and KNN and ensemble methods such as bagging.

The chosen database consisted in more than 250,000 samples of used cars in Germany. The project starts with  with cleaning database and performing Explanatory Data Analysis. The data had a lot of noise and discrepancy and after EDA, the reamining data is about half of the original data. 

Various erros are measured after performing our models. Common errors computed for all of our models  are  mean absolute error, mean squared error, median absolute error, R-squared error. Also accuracy error  is computed for certain relevant models. 

For visualisation, scattered plots comparing tested and predicted prices are done for all models.


### 2-Model Comparison
-Linear Regression :shows overrfitting. 

-Decision Tree: quite low accuracy rate, took 45sec, shows overfitting

-Bagging: took very long time; accuracy rate increases as estimator increases, ran out of memory for higher estimators, plot shows satisfactory predictions fine for under 15000 Euro price

-AdaBoost: CHECK AGAIN. took longer than decisionvtree but less than bagging,

-KNN with cross validation: One of the best models. Very satisfactory r2 squared error value, much faster than bagging

-Random Forest wih cross validation: Even better than KNN, very good r2 squared error value


### 3-Recommendations and Future Work


-Feature Engineering via additional features and feature interaction.

-Data Augmentation via using web scrapping techniques through online used car platforms like immoscout.

-Model Optimization; Hyperparameter Tuning by grid search or random search with cross-validation.

-Using other ensemble methods such as Gradient Boosting, XGBoost, or LightGBM.

-Advanced Machine Learning Techniques such as Neural Networks