# Восстановление золота из руды

Подготовить прототип модели машинного обучения для «Цифры». Компания разрабатывает решения для эффективной работы промышленных предприятий.

Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. Используя данные с параметрами добычи и очистки. 

Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.


Необходимо:

1. Подготовить данные;
2. Провести исследовательский анализ данных;
3. Построить и обучить модель;
4. Провести тестирование.

- import pandas as pd
- import numpy as np
- import seaborn as sns
- from sklearn.dummy import DummyRegressor
- from sklearn.ensemble import RandomForestRegressor
- from sklearn.linear_model import LinearRegression
- from sklearn.metrics import fbeta_score, make_scorer
- from sklearn.metrics import mean_absolute_error
- from sklearn.model_selection import GridSearchCV, cross_val_score
- from sklearn.model_selection import cross_val_score
- from sklearn.pipeline import Pipeline
- from sklearn.tree import DecisionTreeRegressor
