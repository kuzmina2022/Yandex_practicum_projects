# Прогнозирование оттока клиентов банка


## Описание проекта

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.
Нужно построить модель со значением F1-меры не менее 0.59.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **seaborn**
- **matplotlib**
- **scipy**
- sklearn.model_selection.**train_test_split**
- sklearn.utils.**shuffle**
- sklearn.tree.**DecisionTreeClassifier**
- sklearn.ensemble.**RandomForestClassifier**
- sklearn.linear_model.**LogisticRegression**
- sklearn.metrics.**f1_score, roc_auc_score, confusion_matrix**
- sklearn.preprocessing.**StandardScaler**

## Вывод

Были построены модели классификации и выбрана модель с наилучшими показателями метрики f1. Этой моделью оказался случайный лес. Испытание на тестовой выборке показало значение метрики f1 выше требуемого.

 

