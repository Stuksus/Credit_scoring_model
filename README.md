# Оценка экономического эффекта и улучшений от внедрения моделей машинного обучения на данных из банковского сектора в задачах бинарной классификации

## Задача: 
Разработать и внедрить модель кредитного скоринга более лучшего качества. Оценить экономический эфект от внедрения новой модели. 
Для реализации поставленной цели мне будет необходимо:
- Выбрать подходящие для данной задачи алгоритмы
- Получить данные для исследования 
- Предобработать и проанализировать данные 
- На основании данных обучить выбранные алгоритмы и получить модели
- Произвести сравнение моделей и выбор лучшей
- Провести тесты для лучшей модели на корректность предсказаний 
- Сравнить новую модель со старой
- Оценить экономическое эффект от внедрения данной модели  

## Используемые библиотеки и инструменты
- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- catboost
- tqdm
- imblearn
- scipy
- random


## Заключение:
В ходе разработки мы выбрали «лучшую» модель, у который на тестовой выборке метрики получились следующие: 
- ROC-AUC: 0.83
- F_2.5 = 0.52
- Лучший пороговое значение (threshold): 0.58
- Максимальная прибыль: 142 216 528 у.е.

В теме мы ставили перед собой задачу оценить экономический эффект, от внедрения новой модели. Если за старую модель брать, модель, построенную на основе случайного леса, то экономический эффект оказался положительным и составил 903 833 условных единиц (в 1.006 раза больше). Если же за старую модель брать модель предсказания, которой близки к случайным гаданиям, то положительный эффект составит 72 623 942 условных единиц (в 2.04 раза больше)
