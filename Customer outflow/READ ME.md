# Отток клиентов

Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Вам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. 

Постройте модель с предельно большим значением *F1*-меры. Чтобы сдать проект успешно, нужно довести метрику до 0.59. Проверьте *F1*-меру на тестовой выборке самостоятельно.

Дополнительно измеряйте *AUC-ROC*, сравнивайте её значение с *F1*-мерой.

**Библиотеки**

- pandas
- math
- matplotlib pyplot
- numpy
- seaborn
- joblib import dump
- sklearn.ensemble import RandomForestClassifier
- sklearn.dummy import DummyClassifier
- sklearn.linear_model import LogisticRegression 
- sklearn.metrics import accuracy_score
- sklearn.metrics import confusion_matrix
- sklearn.metrics import f1_score
- sklearn.metrics import precision_score, recall_score
- sklearn.metrics import recall_score
- sklearn.metrics import roc_curve 
- sklearn.metrics import roc_auc_score
- sklearn.model_selection import train_test_split
- sklearn.preprocessing import OneHotEncoder
- sklearn.preprocessing import StandardScaler
- sklearn.tree import DecisionTreeClassifier
- sklearn.utils import shuffle
