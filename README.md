# Corporación Favorita Grocery Sales Forecasting
## By Srujana
### January 11, 2021

[Favorita](https://www.corporacionfavorita.com/en/) is one of the major grocery chains in Ecuador, South America. In this [Kaggle](https://www.kaggle.com/c/favorita-grocery-sales-forecasting/data) competition we will be predicting the unit sales for thousands of items sold at different Favorita stores located in Ecuador. 
This project contains six files ( Train, Test, Item, Stores, Oil, Transactions and Holiday_events ) needed for predicting unit sales for different products from 16 August 2017 to 31 August 2017. 

## Main Results

![Feature Importance](imgs/Feature_Importance.png)

The above plot tells about features responsible for predicting unit sales for a particular item in different stores across Ecuador


:fast_forward: Average sales calculated from today to past two weeks 


:fast_forward: Promotions calculated from today to future days. The days mainly responsilble for test data unit sales are Promotions for 0th day,7th day,14th day and 9th day.



## Analysis
:arrow_right: Analyzed the six data files and plotted insights from them to understand the relations between target variable and other variables


:arrow_right: Modeled Random forest regressor and Randomized Search CV models on train and test data



**Evaluation Metrics**

Random Forest Regressor | Randomized Search CV
----------------------- | ---------------------
MAE  :   0.29           |  MAE  :   0.28 
MSE  :   0.40           |  MSE  :   0.35 
RMSE :   0.63           |  RMSE :   0.59


:pushpin: We can observe that MSE reduced .5 with Randomized Search CV by Hyperparameter tuning





## References

Data Source[https://www.kaggle.com/c/favorita-grocery-sales-forecasting/data]


https://www.kaggle.com/aharless/dissecting-ceshine-lee-s-lgbm-kernel 


https://www.kaggle.com/sohinibhattacharya86/predict-grocery-sales-rf-xgb  



