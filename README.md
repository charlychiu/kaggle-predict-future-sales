kaggle-predict-future-sales

[main.ipynb](https://nbviewer.jupyter.org/github/charlychiu/kaggle-predict-future-sales/blob/master/main.ipynb)

|max_depth|n_estimators|min_child_weight|colsample_bytree|validation_0|validation_1|submit score|note|
|--|--|--|--|--|--|--|--|
|8|1000|300|0.8|0.813137|0.905782|0.90646|*best one|
|8|1000|300|0.6|0.820428|0.904658|0.91788||
|10|1000|200|0.8|0.804821|0.901044|0.92135|seems that overfitting|
|10|1000|200|0.8|0.825712|0.906237|0.91378|remain only feature importance top 25 |

Trying to use RandomizedSearchCV or GridSearchCV tuning parameter.  
Both from sklearn.model_selection package.
