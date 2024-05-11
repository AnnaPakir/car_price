# Проект по определению стоимости автомобилей

**Описание проекта:** Автомобиля уже долгие годы являются одним из самых необходимых, но самым дорогим вложением. Цена обмана или ошибки очень велика. Помочь может изучение информации из VIN-кодов. В данном проекте на основе лишь вин-кодов автомобилей создана модель машинного обучения предсказывающая цену автомобиля, а также создано приложение для работы данной модели.

**Цель исследования:** Создать модель машинного обучения,позволяющую определить цену автомобиля по его Vin-коду и разместить данное приложение на Streamlit.

**Используемые технологии:** re, phik, sklearn, lightgbm, pickle, streamlit

**Ход исследования:** Для выполнения цели исследования необходимо будет выполнить следующие задачи:
- Первоначальный анализ и предобработка данных. Загрузка данных, первоначальное их изучение и анализ, их предобработка.
- Исследовательский анализ данных. исследование данных, их корреляция.
- Обучние модели. Создание модели машинного оучения, подбор гипперпараметров, анализ важности признаков.
- Вывод: Описание результатов исследования, выводы. Поле для анализа Вин-кода.
- Создание приложение на Streamlit.

**Выводы:** Была создана модель с метрикой RMSE 3486.1 на тестовой выборке. Модель хорошо определяет стоимость некоторых автомобилей со средней ошибкой около 2000. Мало представленнные, или плохо представленные марки модель не определяет.


Данное исследование может стать основой для анализа стоимости автомобилей.
![plot](https://github.com/AnnaPakir/car_price/blob/main/Video.gif)

[link](https://carprice-annapakir.streamlit.app/)
