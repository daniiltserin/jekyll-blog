---
layout: post
title:  "Новый фреймворк"
date:   2017-01-09 03:13:52 +0600
categories: daniiltserin
---

Я писал на ларавеле, симфони. Но нигде не столкнулся с таким явлением, что код на експрессе то работает, то выдает ошибки. Причем один запуск кода может пройти замечательно, а второй без каких либо изменений в коде не удается и вылетает ошибка. Мне лень разбираться со всеми странностями и я решил создать свой фреймворк, который ляжет в основу Prostopst. 

Из коробки должны идти:

* Модуль для работы с базой данных: MongoDB, Redis.
    - миграции
    - заполнение
* Роутеры
* Авторизация
* Сессии
* CSRF
* Хеширование
* Локализация
* Валидация полей ввода
* Шаблонизаторы и препроцессоры
* Запускатор команд по генерации шаблонов моделей, модулей, middleware и т. п.

Это все что пока на ум приходит.