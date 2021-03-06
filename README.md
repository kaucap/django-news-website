<h1 align="center">Новостной сайт на Джанго</h1>
<p align="center">
<img width="500px" height="500px" src="static/images/logotype.jpg">
</p>

## Описание
Новостной сайт, разработанный на Django. Поддерживает два языка: русский и английский.

## Запуск
- Создать виртуальное окружение. python3 -m venv venv
- Установить нужные библиотеки. pip install -r requirements.txt
- В качестве бд используется Postgres. Нужно установить его.

## Страницы
- '/' - Главная страница, на ней находятся все новости
- 'admin/' - админка
- 'admin/doc/' - документация в админке
- 'news/create_news/' - создание новости
- 'news/pk/' - детальная страница с новостью
- 'news/update_news/pk/' - редактирование новости
- 'news/category/pk/' - новости по категориям
- 'account/registration/' - регистрация пользователя
- 'account/login/' - авторизация пользователя
- 'account/logout/' - выход из профиля
- 'account/username/' - личный кабинет пользователя
- 'api/v1/' - Django DRF

## Функционал DRF
- 'list' - получение списка новостей. Доступен для всех пользователей
- 'create' - создание новости. Доступен для авторизованных пользователей
- 'retrieve' - получение информации о списке новостей, либо о конкретной новости. Доступен для всех пользователей
- 'update' - обновление новости. Доступен админу и автору новости
- 'partial_update' - частичное обновление новости. Доступен админу и автору новости
- 'destroy' - удаление новости. Доступен админу и автору новости
