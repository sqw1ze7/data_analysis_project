# Лабораторная работа 1

## Описание данных
- Набор данных: Titanic
- Источник: Kaggle
- Количество строк: 891
- Количество столбцов: 12

## Состав показателей
1. PassengerId - int64
2. Survived - int64
3. Pclass - int64
4. Name - object
5. Sex - object
6. Age - float64
7. SibSp - int64
8. Parch - int64
9. Ticket - object
10. Fare - float64
11. Cabin - object
12. Embarked - object

## Используемые библиотеки
- pandas==1.5.3
- numpy==1.24.3
- matplotlib==3.7.1
- seaborn==0.12.2

## Методы предобработки
1. `.fillna()` - заполнение пропущенных значений
2. `.astype()` - преобразование типов данных
3. `.isnull().sum()` - поиск пропущенных значений
4. `.describe()` - описательная статистика
