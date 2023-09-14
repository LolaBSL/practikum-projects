# Проект "Промышленность"

**Цель проекта:**

Оптимизация производственных расходов на металлургическом комбинате ООО «Так закаляем сталь» посредством уменьшения потребления электроэнергии на этапе обработки стали. 

Необходимо построить модель, которая предскажет температуру стали.

- import pandas as pd
- import matplotlib.pyplot as plt
- import numpy as np
- import seaborn as sns
- from datetime import timedelta
- from catboost import CatBoostRegressor
- from sklearn.ensemble import RandomForestRegressor
- from sklearn.linear_model import LinearRegression
- from sklearn.metrics import mean_absolute_error
- from sklearn.model_selection import train_test_split
- from sklearn.model_selection import cross_val_score
- from sklearn.model_selection import GridSearchCV
- import warnings
