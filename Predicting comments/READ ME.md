# Проект для «Викишоп»

Для нового сервиса интернет-магазина «Викишоп». Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. 

***Цель:*** создать инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. 

***Задача:*** Обучить модель классифицировать комментарии на позитивные и негативные. В распоряжении набор данных с разметкой о токсичности правок.
Метрика качества *F1* не меньше 0.75. 


- import pandas as pd
- import matplotlib.pyplot as plt
- import numpy as np
- from catboost import CatBoostClassifier
- import nltk
- from nltk.corpus import stopwords
- from nltk.tokenize import word_tokenize
- from pymorphy2 import MorphAnalyzer
- import re
- from sklearn.feature_extraction.text import TfidfVectorizer
- from sklearn.linear_model import LogisticRegression
- from sklearn.metrics import f1_score
- from sklearn.model_selection import cross_val_score
- from sklearn.model_selection import GridSearchCV
- from sklearn.model_selection import train_test_split
- from sklearn.pipeline import Pipeline, make_pipeline
- from sklearn.utils import shuffle
- import spacy
- from tqdm.notebook import tqdm
- tqdm.pandas()
