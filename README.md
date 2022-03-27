
Русская инструкция
==================


* Версии PHP: 7.1.33.
* Сервер баз данных MySQL 5.7.33.
* Веб-сервер Apache.

---------
Установка
---------

#. Установите ``Open Server``, ``Mamp`` или любой другой локальный сервер.
#. Склонируйте репозиторий с файлами

    .. code-block:: bash

        $ git clone https://github.com/MrMangust/SimtechDev.git 
        $ cd "папка сервера"

#. Импортируйте базу данных с демо датой.

#. Запуск приложения
* Для отправки формы перейдите по адресу localhost/feedback.php
* Просмотр обращений и пользователей доступен после авторизации в форме index.php. Используйте данные admin@mail.ru/admin
* При отправке формы на почту приходит письмо. 
-------------------
Подключение к MySQL
-------------------

Подключение к базе данных осуществляется через файл connect.php
Там же находятся данные для работы с smtp.gmail.com
Дамп БД содержит 2 базы (users и feedback).


------------------
Отправка e-mail'ов
------------------
Отправка e-mail'ов осуществляется через smtp, настройками Open Server.