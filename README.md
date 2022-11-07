API Yatube

Апи для сервиса Yatube

Возможности

Получение постов для любых пользователей
Написание постов для авторизированных пользователей
Разбиение постов на группы
Получение и работа с комментариями к постам
Подписка на авторов


Установка

Установите виртуальное окружение:

$python3 -m venv venv

После установки запустите его:

$source venv/bin/activate

Установите зависимости из requirements.txt:

$pip install -r reqiurements.txt

Выполните миграции:

$cd yatube_api
$python3 manage.py makemigrations
$python3 manage.py migrate

Запустите сервер:

$python3 manage.py runserver

Апи доступен по адресу http://127.0.0.1:8000/api/v1/

Документация

Вся документация доступна по ссылке: http://127.0.0.1:8000/redoc/#tag/api