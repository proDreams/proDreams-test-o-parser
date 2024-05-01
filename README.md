## Тестовое задание для компании POPSO (ИП Варламов Алексей Николаевич).

## Задача:

Реализовать Django-приложение с REST API для парсинга товаров со страницы магазина на ozon.ru и выдачей полученной
информации.  
Также в дополнение необходимо реализовать Telegram-бота для отправки уведомлений об окончании парсинга и
выводе результатов последнего парсинга.

## Используемые технологии:

- `Django` + `Django REST Framework` - основа проекта.
- `drf-spectacular` - для создания API документации.
- `Celery` + `Redis` - для создания очереди задач на парсинг.
- `Beautiful Soup` - для парсинга сайта.
- `Jazzmin` - современный шаблон для панели администратора Django.
- `aiogram` - основа Telegram-бота.
- `requests` - для выполнения HTTP-запросов.

## Запуск:

1. Переименовать файл `.env.example` в `.env` и заполнить соответствующими данными.
2. Выполнить команду `docker compose up -d`
3. Бот запустится и уведомит администратора о запуске. Сайт будет доступен по адресу `http://<ip_сервера>:8000/`.

## Скриншоты:

Панель администратора:
![Панель администратора](./images/img.png)  
Результаты парсинга:
![Результаты парсинга](./images/img_1.png)  
![Результаты парсинга](./images/img_2.png)
![Результаты парсинга](./images/img_3.png)  
Товары:
![Товары](./images/img_4.png)
Запуск парсинга в боте:
![Запуск парсинга в боте](./images/img_5.png)
Уведомление в боте:
![Уведомление в боте](./images/img_6.png)
Результат последнего парсинга:
![Результат последнего парсинга](./images/img_7.png)
