# Проекты Data Science
Репозиторий проектов Data Science, Data Analysis, Machine Learning

| Проект        | Описание      | Стек          |
| ------------- | ------------- | ------------- |
[Определение стоимости автомобилей](https://github.com/Chipelin/data-science-projects/tree/main/auto_service_ml) | Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение, чтобы привлечь новых клиентов. В нём можно будет узнать рыночную стоимость своего автомобиля. Постройте модель, которая умеет её определять. В вашем распоряжении данные о технических характеристиках, комплектации и ценах других автомобилей. |  Pandas LightGBM Catboost sklearn |
|[ Отток клиентов](https://github.com/Chipelin/data-science-projects/tree/main/bankchurn) | Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. |  Pandas sklearn |
|[ Проект для «Викишоп»](https://github.com/Chipelin/data-science-projects/tree/main/comments_ml) | Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. В файле comments_ml_mk2_with_bert содержится имплементация языковой модели Bert.| Pandas LightGBM sklearn Bert |
|[ Защита персональных данных клиентов](https://github.com/Chipelin/data-science-projects/tree/main/data_protection_ml) | Нужно защитить данные клиентов страховой компании «Хоть потоп». Разработайте такой метод преобразования данных,чтобы по ним было сложно восстановить персональную информацию.|  Pandas sklearn seaborn|
|[ Оценка платежеспособности](https://github.com/Chipelin/data-science-projects/tree/main/data_refactoring) | Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов. Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.| Pandas|
|[Восстановление золота из руды](https://github.com/Chipelin/data-science-projects/tree/main/gold_ml) | Прототип модели машинного обучения для «Цифры». Компания разрабатывает решения для эффективной работы промышленных предприятий.| Pandas sklearn |
|[Рекомендация тарифов](https://github.com/Chipelin/data-science-projects/tree/main/mobile_ml) | Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».| Pandas sklearn |
|[Выбор локации для скважины](https://github.com/Chipelin/data-science-projects/tree/main/oil_ml) |Предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. Постройте модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. Проанализируйте возможную прибыль и риски техникой Bootstrap.| Pandas sklearn |
|[Яндекс Недвижимость](https://github.com/Chipelin/data-science-projects/tree/main/real_estate) |Яндекс Недвижимость — архив объявлений за несколько лет о продаже квартир в Санкт-Петербурге и соседних населённых пунктах. Задача — выполнить предобработку данных и изучить их, чтобы найти интересные особенности и зависимости, которые существуют на рынке недвижимости. О каждой квартире в базе содержится два типа данных: добавленные пользователем и картографические. Например, к первому типу относятся площадь квартиры, её этаж и количество балконов, ко второму — расстояния до центра города, аэропорта и ближайшего парка.| Pandas Seaborn|
|[Прогнозирование заказов такси](https://github.com/Chipelin/data-science-projects/tree/main/taxi_ml) |Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Необходимо построить модель для такого предсказания.|Pandas sklearn LightGBM  Catboost|
|[Яндекс Музыка](https://github.com/Chipelin/data-science-projects/tree/main/yandex_music) |Сравнение на данных Яндекс Музыки поведения пользователей двух столиц.|Pandas|
|[Разработка принципов прогнозирования успешности продуктов](https://github.com/Chipelin/data-science-projects/tree/main/video_game_store) |Интернет-магазине «Стримчик», продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании. | Pandas scipy seaborn |
|[Определение возраста покупателей](https://github.com/Chipelin/data-science-projects/tree/main/computer_vision_ml) |Сетевой супермаркет «Хлеб-Соль» внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы: Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;Контролировать добросовестность кассиров при продаже алкоголя. Необходимо построить модель, которая по фотографии определит приблизительный возраст человека. В нашем распоряжении набор фотографий людей с указанием возраста.| Pandas Matplotlib Tensorflow Keras|
|[Телеком](https://github.com/Chipelin/data-science-projects/tree/main/telecom_ml) |Оператор связи «Ниединогоразрыва.ком» хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.| Pandas Matplotlib LightGBM Catboost Sklearn Phik|




