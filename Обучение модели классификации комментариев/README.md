# Классификация комментариев


## Описание проекта

Требуется анализировать комментарии пользователей на английском языке и выделять токсичные, чтобы отправить на модерацию.



## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **spacy**
- nltk.stem.**WordNetLemmatizer**
- nltk.corpus.**stopwords**
- sklearn.feature_extraction.text.**TfidfVectorizer**
- sklearn.linear_model.**LogisticRegression**
- sklearn.ensemble.**RandomForestClassifier**
- sklearn.model_selection.**cross_val_score, GridSearchCV**
- sklearn.preprocessing.**StandardScaler**
- sklearn.metrics.**f1_score**
- sklearn.utils.**shuffle**
- sklearn.preprocessing.**StandardScaler**
- lightgbm.**LGBMClassifier**


## Вывод

Была проведена исследовательская работа по обработке текстов и обучению и выбору модели для определения токсичных комментариев по методу TF-IDF. Наилучшие результаты показала модель LGBM.
