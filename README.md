# German second hand car price prediction using following methods:

### 1-Summary

In this project six different models are used to predict the price of second hand cars based on the following selected features: year, power per kw, mileage in km and brand. The models used are: Linear Regression, Decision Tree, Bagging, AdaBoost, K-Nearest Neighbours and Random Forest.

The chosen database consisted in more than 250,000 samples of used cars in Germany. The project starts 
with cleaning database and performing Explanatory Data Analysis (eda.ipynb). The data had a lot of noise and discrepancy and after EDA, the reamining data is about half of the original data. 

Various erros are measured after performing our models on training and testing data using cross-validation. Common errors computed for all of our models  are  mean absolute error, median absolute error, R-squared error. Also accuracy error  is computed for certain relevant models. 

For visualisation, scattered plots comparing tested and predicted prices are done for all models.


### 2-Model Comparison

The best performance was for KNN and Random Forest, given their R2 error as well as mean absolute and median absolute errors. This can be due to the diversity and sporadicity of the data. The predictions done by linear regression, decision tree regression, bagging and adaboost consider a lot of samples in order to  do prediction, while KNN and random forest choose the nearest samples which filters many non-redundant samples that were used in other models.


### 3-Recommendations and Future Work


-Feature Engineering via additional features and feature interaction.

-Data Augmentation via using web scrapping techniques through online used car platforms like immoscout.

-Model Optimization; Hyperparameter Tuning by grid search or random search with cross-validation.

-Using other ensemble methods such as Gradient Boosting, XGBoost, or LightGBM.

-Advanced Machine Learning Techniques such as Neural Networks