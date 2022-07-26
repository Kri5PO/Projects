# Построение модели определения стоимости автомобиля

`Интернет-сервисы` `Интернет-магазины` `Бизнес`

## Описание проекта

Сервис по продаже автомобилей с пробегом  разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторических данных необходимо построить модель для определения стоимости автомобиля.

## Статус проекта

ЗАВЕРШЕН

## Решение

`Python` `Pandas` `NumPy` `Matplotlib` `Time` `CatBoost` `LightGBM` `XGBoost` `Scikit-learn` `category_encoders`

Проведена предобработка данных. Обучено три модели градиентного бустинга. Рассмотрено качество и скорость работы моделей. Увеличена скорость работы моделей корректировкой гиперпараметров и отбором признаков. По результатам выбрана лучшая модель.

## Результат

- Лучшая модель: XGBRegressor(max_depth=10, random_state=123)
- время обучения - 8 секунд,
- время предсказания - 0 секунд,
- RMSE на обучающей выборке - 1033,
- RMSE на тестовой выборке - 1365.

[Открыть Notebook](https://github.com/Kri5PO/Projects/blob/main/10_Построение_модели_определения_стоимости_автомобиля/auto.ipynb)


```python

```
