# Прогнозирование количества заказов такси на следующий час

## Описание проекта

Требуется спрогнозировать количество заказов такси на следующий час, чтобы привлекать больше водителей в период пиковой нагрузки.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**
- statsmodels.tsa.seasonal.**seasonal_decompose**
- sklearn.model_selection.**TimeSeriesSplit**
- sklearn.model_selection.**cross_val_score, GridSearchCV**
- sklearn.preprocessing.**StandardScaler**
- sklearn.metrics.**mean_squared_error**
- sklearn.linear_model.**LinearRegression**
- sklearn.ensemble.**RandomForestRegressor**
- catboost.**CatBoostRegressor**
- **lightgbm**

## Общий вывод

Проведено исследование временного ряда на предмет трендовых и сезонных закономерностей, случайной составляющей. Проведено исследование 4х типов моделей, выбрана модель LightGBM.
