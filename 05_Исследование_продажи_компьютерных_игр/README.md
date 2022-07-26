# Исследование продажи компьютерных игр

`Компьютерные игры`

## Описание проекта

Интернет-магазин «Стримчик» продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Необходимо выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

Представлены данные до 2016 года. Нужно отработать принцип работы с данными при планировании кампании на 2017-й. Неважно, прогнозируете ли вы продажи на 2017 год по данным 2016-го или же 2027-й — по данным 2026 года.

## Статус проекта

ЗАВЕРШЕН

## Решение

`Python` `Pandas` `Seaborn` `Plotly` `Matplotlib` `Pylab` `NumPy`

Проведена предобработка данных. На этапе расчетов добавлена дополнительная информация. Проведен исследовательский анализ: определено сколько игр выпускалось в разные годы и как менялись продажи по платформам. Составлен портрет пользователя каждого региона: определены самые популярные платформы и жанры. Исследовано влияние рейтинга ESRB на продажи.

Проверены две гипотезы:
- Средние пользовательские рейтинги платформ Xbox One и PC одинаковые.
- Средние пользовательские рейтинги жанров Action и Sports разные.

## Результат

Исследование **самых популярных платформ (топ-5) для пользователя каждого региона** показало, что топ-5 отличается в разных регионах и в разные годы, пользователи Сев. Америки и Европы похожи в своих предпочтениях, предпочтения пользователей из Японии отличаются от европейский и североамериканских. Лидеры продаж за актуальный период в Сев. Америке - платформа **XOne**, в Европе - **PS4**, в Японии - **3DS**. Во всех трех регионах в топ-5 лидеров продаж входят две платформы - **PS4 и WiiU**.

Исследование **самых популярных жанров (топ-5) для пользователя каждого региона** показало, что топ-5 популярных жанров отличается в разных регионах и в разные годы. Пользователи Сев. Америки и Европы похожи в своих предпочтениях в жанрах, а предпочтения пользователей из Японии отличаются от европейский и североамериканских. Лидеры продаж за актуальный период в Сев. Америке и Европе - жанр **Shooter**, в Японии - жанр **Role-Playing**. Во всех трех регионах в топ-5 лидеров продаж входят два жанра - **Role-Playing и Platform**.

Исследование **влияния рейтинга ESRB на продажи в отдельном регионе** показало, что предпочтение игр по возрастному рейтингу ESRB почти не отличается в разных регионах, но отличается в разные годы. Пользователи Сев. Америки, Европы и Японии очень похожи в своих предпочтениях игр по возрастному рейтингу ESRB. В актуальный период в Сев. Америке и в Европе лидируют игры с рейтингом **М (Для взрослых)**, в Японии - игры **без рейтинга ESRB**.

- Гипотеза о том, что **средние пользовательские рейтинги платформ Xbox One и PC одинаковые** не подтвердилась.
- Гипотеза о том, что **средние пользовательские рейтинги жанров Action и Sports разные** не подтвердилась.

*Проект выполнен в двух вариантах оформления: с использованием библиотеки **Plotly** и библиотеки **Seaborn**.*

[Открыть Notebook с Plotly](https://github.com/Kri5PO/Projects/blob/main/05_Исследование_продажи_компьютерных_игр/games_plotly.ipynb)

[Открыть Notebook с Seaborn](https://github.com/Kri5PO/Projects/blob/main/05_Исследование_продажи_компьютерных_игр/games_seaborn.ipynb)


```python

```
