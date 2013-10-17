SmoothStart
===========

Плавный запуск мощной нагрузки на ATtiny13

Проект разрабатывается для интеграции в самодельный сверлильный станок, сделанный из микроскопа.


Основные функции:

1. Плавное включение/выключение двигателя
2. Плавное включение/выключение подсветки


Все управление будет реализовано одной кнопкой, по следующему алгоритму

1. Короткое нажатие кнопки - включение/отключение подсветки
2. Среднее нажатие кнопки - включение/отключение двигателя
3. Длинное нажатие кнпки - отключение двигателя и подсветки


Задачи

1. Разработать принципиальную схему устройства
2. Разработать и изготовить печатную плату устройства, с учетом особенностей предполагаемого места установки
3. Разработать прошивку микроконтроллера


Цели проекта:

1. Изучение работы ШИМ, таймеров и прерываний МК
2. Получение опыта комплексной разработки (от постановки задачи до начала использования)
3. Разработка устройства для дальнейшего применения
