# Определение возраста покупателей

Для сетевого супермаркета «Хлеб-Соль», которая внедряет систему компьютерного зрения для обработки фотографий покупателей.

Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы:
Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;
Контролировать добросовестность кассиров при продаже алкоголя.

***Задача:***

Постройте модель, которая по фотографии определит приблизительный возраст человека. 

Для выполнения задачи есть набор фотографий людей с указанием возраста.

***Необходимо:***

- Провести анализ набора фотографий;
- Подготовить данные для обучения модели;
- Провести обучение на нейронной сети и привести качество МАЕ к менее 8;
- Сделать выводы.

**Библиотеки**

- pandas
- math
- matplotlib pyplot
- numpy
- PIL import Image
- tensorflow.keras.preprocessing.image import ImageDataGenerator
- tensorflow as tf
- tensorflow.keras.models import Sequential
- tensorflow.keras.optimizers import Adam
- tensorflow.keras.preprocessing.image import ImageDataGenerator
- tensorflow.keras.applications.resnet import ResNet50
- tensorflow.keras.layers import GlobalAveragePooling2D, Dense
- tensorflow import keras
