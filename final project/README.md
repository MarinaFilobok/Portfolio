# Выпускной проект

Финальный спринт включает в себя работу над проектом, дашборд, задачи по A/B-тестированию и SQL.
Задача: Анализ данных для e-commers.
Интернет-магазин товаров для дома «Пока все ещё тут» в срочном порядке ищет аналитиков. 
Вы поможете нашему магазину стать лучше, а клиентам — обустроить дом своей мечты. 
Наши ближайшие задачи — выявление профилей покупателей, а также полноценный анализ товарного ассортимента.
«Пока все ещё тут» — мы создаём уют!


## Часть I: [E-commerce — Выявление профилей потребления](https://github.com/MarinaFilobok/Portfolio/blob/3c27dca84ef55d7ea48b11494eb3ef1d00dfe92b/final%20project/1_e-commers.ipynb)

### Цель исследования
Цель проекта - сегментировать покупателей по профилю потребления для создания персонализированных предложений.

Работа состоит из 6 частей:

- Загрузка данных
- Предобработка данных (исследовать пропущенные значения, дубликаты, типы данных, наименование колонок, проверка на бизнес-правила "1 заказ - 1 клиент" и "1 заказ" - "1 дата")
- Исследовательский анализ данных (добавление необходимых столбцов: общее количество заказов у клиента, средний чек клиента, сумма общих покупок клиента, сумма текущего заказа)
- Сегментирование покупателей по профилю потребления (с исспользованием RFM-анализа, для этого используем 3 метрики: давность заказа, частота покупок и сумма покупок)
- Формулировка и проверка статистических гипотез:
  - Гипотеза о различии среднего чека в группах
  -  Гипотеза о различии количества заказов в группах
- Презентация и итоговый вывод
В итоге работы мы получим информацию о том, на какие группы мы можем разделить покупателей для внедрения персонализированных предложений. Также мы подтвердим или опровергнем наши гипотезы.

### Используемые библиотеки

*pandas, numpy, matplotlib, seaborn, scipy*


## Часть II: [A/B-тестирование](https://github.com/MarinaFilobok/Portfolio/blob/20868213082e71fd010f1e5d8defb7751af39f9b/final%20project/2_A_B_test.ipynb)

### Цель исследования
Проведение оценки результатов A/B-теста после введения улучшенной программы рекомендаций для региона EU.

### Входные данные 
- датасет с действиями пользователей,
- вспомогательные датасеты (данные о пользователях, календарь маркетинговых событий и пр.),
- Техническое задание.

Работа состоит из 7 частей:

- Загрузка данных
- Предобработка данных
- Соответствие данный ТЗ
- Продуктовая воронка
- Исследовательский анализ данных
- Оценка A/B-теста
- Общий вывод и рекомендации
  
В итоге работы мы оценим результат A/B-теста и напишем рекомендации к дальнейшей работе.
### Используемые бибилотеки

*pandas, numpy, matplotlib, seaborn, math, datetime, scipy*

## Часть III: [SQL](https://github.com/MarinaFilobok/Portfolio/blob/20868213082e71fd010f1e5d8defb7751af39f9b/final%20project/3_SQL_final.ipynb)

### Цель: 
Проанализировать базу данных крупного сервиса для чтения книг по подписке.

В ней — информация о книгах, издательствах, авторах, а также пользовательские
обзоры книг. 

### Задачи:

- Посчитать,сколько книг вышло после 1 января 2000 года;
- Для каждой книги посчитать количество обзоров и среднюю оценку;
- Определить издательство, которое выпустило наибольшее число книг толще 50 страниц — так мы исключим из анализа брошюры;
- Определить автора с самой высокой средней оценкой книг — учитывайте только книги с 50 и более оценками;
- Посчитать среднее количество обзоров от пользователей, которые поставили больше 48 оценок.

### План проекта:

- Устанавливаем и импортируем необходимые библиотеки
- Предобработка данных
- Решаем задачи с помощью SQL запроса
- Итоговый вывод