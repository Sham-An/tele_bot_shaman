source venv37/bin/activate
. /opt/PycharmProjects/tele_bot/venv37/bin/activate
cd avito_parser_django/avito
python manage.py runserver

/admin vladimir:111

Описание
========

Примеры кода из видео-уроков канала ["IT Каждый день"](https://www.youtube.com/channel/UCAlRksF5338XmSMbwS3W7eA/)

Используется Python 3.7 или старше


Контакты
========

* Канал в Telegram: https://telegg.ru/it_everyday
* Заказать бота: https://telegg.ru/kasatkin_v
* Научиться программировать самостоятельно: http://bit.ly/34wnx10


Настройка
=========

Установка зависимостей:

```
pip install -r pip-requirements.txt
```

Запуск бота на локальной машине:

```
export PYTHONPATH=$(pwd)
export TG_CONF=development
python echo/main.py
```

Так же в каждой из папок могут быть дополнительные зависимости.
Подробнее смотрите в соответствующих видео.

Удачи!
