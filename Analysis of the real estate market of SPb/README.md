# Исследование объявлений о продаже квартир

## **Цель:**
Анализ данных о продажах квартир в Санкт-Петербурге и Ленинградской области за последние несколько лет для выявления параметров, влияющих на рыночную стоимость квартиры. Данное исследование поможет пользователям сервиса Яндекс.Недвижимость осознанно выбирать квартиру для приобретения, ориентируясь на праметры, которые наиболее сильно влияют на цену объекта.

## **План работы:**
1. Загрузка данных и первичное изучение предоставленных данных
2. Предобработка данных (заполнение или удаление пропусков, преобразование типов данных, замена и удаление дубликатов, обработка аномальных значений)
3. Добавление в таблицу новых параметров, необходимых для дальнейшего исследования.
4. Проведение исследовательского анализа данных(изучение параметров, анализ факторов, влияющих на стоимость квартир, построение графиков, отражающих проведенный анализ)
5. Общий вывод

## **Выводы:**

- **Параметры которые наиболее сильно влияют на цену квартиры.**
  
Общая площадь, жилая площадь, площадь кухни и количество комнат наиболее сильно влияют на стоимость квартиры. Коэфицент Пирсона между данными показателями и стоимостью квартиры составляет 0,5, 0,5 и 0,3 соответственно. Чем выше общая площадь, жилая площадь или площадь кухни, тем выше стоимость квартиры. Чем больше комнат в квартире, тем выше стоимость. Кроме того, показатель типа этажа (первый, последний, другой) также имеет незначительное влияние на цену квартиры. Первый этаж стоит дешевле всего, он сильно снижает стоимость квартиры. Последний этаж также снижает стоимость квартиры, но не так сильно как первый этаж. Если этаж не первый и не последний, стоимость не варьируется среди других этажей.

- **Сроки продажи квартиры.**
  
Средним сроком продажи квартиры является около 155 дней.

- **Распределение стоимости квартиры в зависимости от расположения.**
  
Наиболее дорогой квадратный метр квартиры в Санкт-Петербурге. Средняя цена квартиры составляет 7,3 млн рублей. Последним городом в топ-10 является Выборг. Средняя стоимость квартиры там составляет 3,2 млн. рублей.

- **Зависимость цены квартиры от отдаленности от центра в Санкт-Петербурге.**
  
Цены на квартиры зависят от отдаленности от центра в Санкт-Петербурге. Чем дальше от центра, тем квартира там дешевле.

## **Использованные библиотеки:**
*pandas, matplotlib, datetime*
