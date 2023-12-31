# E-commerce — Выявление профилей потребления интернет-магазина товаров для дома и быта «Пока все ещё тут»

## Описание проекта

Интернет-магазин товаров для дома «Пока все ещё тут» хочет проанализировать свои данные. Нам нужно помочь магазину стать лучше, а клиентам — обустроить дом своей мечты.

Наши задачи: сегментировать покупателей по профилю потребления для осуществления рекламных рассылок, проанализизировать товарный ассортимент, выделить категории товаров и проанализировать их популярность и сезонность.

## Цели исследования:

1. При предобработке данных разбить все товары на категории (5-7шт.)

2. EDA Провести исследовательский анализ данных:
- Корелляции и анализ количественных признаков, фильтр выбросов
- Топ 10 наимерований новара
- Сумма продаж по месяцам
- Кол-во заказов по месяцам
- Доли категорий
- Сумма продаж по категориям
- Сумма продаж по категориям по месяцам

3. Сегментация/кластеризация покупателей по профиля потребления:
- Стандартизация, Дендограмма, определить оптимальное кол-во кластеров
- Сегментация/кластеризация методом K-Means покупателей по матрице X для каждого пользователя = [Кол-во товара среднее 'quantity', Цена товара средняя 'price', Сумма заказа средняя, Количество заказов покупателя]
- Графики распеределения всех признаков по кластерам

4. Проверка гипотез:
    * 1. Проверка гипотез на различие между средними чеками кластеров (все комбинации)
    * 2. Проверка гипотез на различие между средней ценой 1 товара по кластерам (все комбинации)
    * 3. Проверка гипотез на различие между средним Кол-вом товаров в заказе по кластерам (все комбинации)

## Описание данных:

Датасет описывает транзакции интернет-магазина товаров для дома и быта «Пока
все ещё тут».

Колонки в '/datasets/ecom_dataset_upd.csv':

- date — дата заказа;
- customer_id — идентификатор покупателя;
- order_id — идентификатор заказа;
- product — наименование товара;
- quantity — количество товара в заказе;
- price — цена товара.

## Общий вывод: 
Поработал с текстом, выделил категории товаров и проанализировал их популярность и сезонность, провел EDA товарного ассортимента, кластеризовал покупателей на 4 группы, проанализировал каждый кластер и написал рекомендации по ним.
Более подробно можно посмотреть в проекте.
