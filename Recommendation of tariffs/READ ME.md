# Рекомендация тарифов

В вашем распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы (из проекта курса «Статистический анализ данных»). Нужно построить модель для задачи классификации, которая выберет подходящий тариф. Предобработка данных не понадобится — вы её уже сделали.

Постройте модель с максимально большим значением *accuracy*. Чтобы сдать проект успешно, нужно довести долю правильных ответов по крайней мере до 0.75. Проверьте *accuracy* на тестовой выборке самостоятельно.

- import pandas as pd
- import numpy as np
- from joblib import dump
- from sklearn.dummy import DummyClassifier
- from sklearn.ensemble import RandomForestClassifier
- from sklearn.linear_model import LinearRegression
- from sklearn.linear_model import LogisticRegression 
- from sklearn.metrics import accuracy_score
- from sklearn.metrics import mean_squared_error
- from sklearn.model_selection import train_test_split
- from sklearn.tree import DecisionTreeClassifier
