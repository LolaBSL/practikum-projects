# Защита персональных данных клиентов

**Задача:**

Защитить данные клиентов страховой компании «Хоть потоп». 

Разработать такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. 

Обосновать корректность его работы.


- import pandas as pd
- import matplotlib.pyplot as plt
- import numpy as np
- from numpy.linalg import inv
- from scipy import stats as st
- from sklearn.model_selection import train_test_split
- from sklearn.linear_model import LinearRegression
- from sklearn.metrics import r2_score
