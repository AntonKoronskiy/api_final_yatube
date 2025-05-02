# api_final
api final
# Проект api yatube final 
"API-Yatube" - социальная сеть, в которой пользователи могут опубликовывать, создавать посты, подписываться на других пользователей, следить и комментировать посты других пользователей, создавать группы.

## Используемые технологии
[Python] v3.10.0 - интерпретируемый язык программирования
[Django] v3.2.16  - фрейморк для создания веб-приложений на Python
[Django Rest Framework] v3.12.4 - набор инструменов для создания веб-приложений и API на основе Django

## Запуск проекта
Клонирование прокта
```bash
$ git clone 
```

Создание и активирование виртуального окружения
```bash
$ python -m venv venv
$ . venv/Scripts/activate
```

Установка зависимостей из файла requirements.txt
```bash
$ pip install -r requirements.txt
```

Создание и выполнение миграций
```bash
python manage.py makemigrations
python manage.py migrate
```

Запуск проекта
```bash
$ python manage.py runserver
```