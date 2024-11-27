# HousePricePrediction_ML

### Description:
This project is to predict the housing price based on certain factors like house area, bedrooms, furnished, nearness to mainroad, etc. The dataset is small yet, it's complexity arises due to the fact that it has strong multicollinearity. This dataset is taken from Kaggle. (https://www.kaggle.com/datasets/yasserh/housing-prices-dataset)

### Objective:
1. To understand the Dataset & cleanup (if required).
2. To build Regression models to predict the sales w.r.t a single & multiple feature.
3. Also to evaluate the models & compare thier respective scores like R2, RMSE, etc.

### Things I have done with this dataset:
1. Loaded the dataset, imported all the required libraries, performed basic dataframe info.
2. Visuaizations done to check for outliers, correlation among the features, plotted bar plots, scatter plots, pie charts etc.
3. Applied one hot encoding, Standardization, Cheked for multi collinearity, applied VIF, PCA
4. The following models are covered in this:
   1. Linear Regression
   2. Decision Tree Regressor
   3. Support Vector Regressor (SVR)
   4. K-Nearest Neighbors (KNN) Regressor
   5. Random Forest Regressor
   6. Gradient Boosting Regressor
   Also each model are evaluated using R², RMSE, MSE, MAE metrics.
6. Checked for overfitting and Regularization techniques are applied.

