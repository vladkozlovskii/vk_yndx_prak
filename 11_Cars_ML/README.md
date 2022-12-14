# Определение стоимости автомобилей  
Первый проект с применением моделей градиентного бустинга (здесь LightGBM). Решается задача регрессии - целевая метрика rmse.  
В проекте достаточно большую часть занимает предобработка данных, также много внимания уделяется параметрам LightGBM. Ведется кросс-валидация и подобор параметров для различных моделей. Используются разные способы работы с категориальными признаками


## Цель:
Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. Предоставлены исторические данные: технические характеристики, комплектации и цены автомобилей. Нужно построить модель для определения стоимости.

## Вывод:
- быстрее всего Линейная регрессия (но плохо соответствует целевой метрике), медленне всех RandomForest (второе место по качеству, но несильно отличается от третьего)
- лучше всего показывает себя LightGBM - самый качественный результат с настройкой гиперпараметров при этом достаточно быстро работает (почти как DummyRegressor), без настройки выдает результат чуть хуже, чем RandomForest, но значительно быстрее (примерно как DecisionTree)
- наиболее важные признаки: мощность, год, модель, индекс и марка машины
- Модели сделанные после преобразования OHE считаются медленнее, чем после Ordinal
- LightGBM c настройкой гиперпараметров даёт самый лучший результат 
- Линейная регрессия дает результат хуже, чем другие модели (но все дают результат лучше, чем DummyRegressor)

## Стек технологий:
библиотеки pandas, matplotlib, seaborn, sklearn. Модели: LinearRegression, LightGBMRegressor, DecisionTreeRegressor, Кросс-валидация.

## Статус проекта:
Завершен
