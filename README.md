## Data Source
The Data was obtained from [krishnaik06](https://github.com/krishnaik06/AQI-Project)
## Data visualization and analysis
-  [Seaborn](https://github.com/mohan696matlab/Air_quality_index_Bangalore_-2013-2018/blob/master/Data_Visualization.ipynb)
- [PCA Analysis](https://github.com/mohan696matlab/Air_quality_index_Bangalore_-2013-2018/blob/master/PCA.ipynb)

## Various Regression Algorithm were performed
1. [Linear Regression](https://github.com/mohan696matlab/Air_quality_index_Bangalore_-2013-2018/blob/master/Regression.ipynb) **MSE(Mean Squared Error) = 3687.543**
2. [Support Vector Regression](https://github.com/mohan696matlab/Air_quality_index_Bangalore_-2013-2018/blob/master/SVR_Regression.ipynb) with 'rbf' kernel **MSE = 4262.32**
3. [Decision Tree Regression](https://github.com/mohan696matlab/Air_quality_index_Bangalore_-2013-2018/blob/master/Decission_Tree_Regression.ipynb) **MSE=2330.33**
4. [Random Forest Regression](https://github.com/mohan696matlab/Air_quality_index_Bangalore_-2013-2018/blob/master/Random_forest_Regression.ipynb) **MSE = 1528.96**
5. [Artificial Neural Network Regression](https://github.com/mohan696matlab/Air_quality_index_Bangalore_-2013-2018/blob/master/ANN_Regression.ipynb) **MSE = 2330.89**
6. [XG-Boost Regression](https://github.com/mohan696matlab/Air_quality_index_Bangalore_-2013-2018/blob/master/XG_Boost_Regression.ipynb) **MSE = 1344.67**
## Grid Search CV on XG_boost to findout best hyperparameters
[XG_Boost](https://github.com/mohan696matlab/Air_quality_index_Bangalore_-2013-2018/blob/master/Grid_search_CV_XG_Boost.ipynb) with **max_depth=8** and **n_estimators=25**, yeilded even better results **MSE=1255.65**
