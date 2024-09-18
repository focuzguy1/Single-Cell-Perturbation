# Single-Cell-Perturbation
The problem involves predicting the responses of single cells to various perturbations. Perturbation refers to the application of small molecules or drugs to the cells, which can alter their gene expression. This is crucial for understanding drug efficacy and cellular behavior under different conditions.
This model outperforms numerous existing machine learning models in predicting gene expression levels, achieving an ideal fold score of 0.894 in terms of mean row-wise RMSE. The comparative findings are as follows: The Best fold score for the neural network model is 0.894. Root Mean Squared Error (RMSE) for the test set for Lasso Regression is 1.117, while the RMSE for Random Forest Regressor is 1.116. LinearSVR achieved an RMSE of 1.152 on the test set. The total RMSE for all the data is 0.867. However, the RMSE for the previous method was shown to be 1.962 Table 1. The previous method introduced multiple algorithms to handle different machine learning tasks. The prior approach made use of a wide range of algorithms, such as RandomForestClassifier, Ridge, CatBoostRegressor, and MultiOutputRegressor. These algorithms were selected to achieve reliable and accurate predictive modeling, taking into account the nuances and complexity included in the dataset.
