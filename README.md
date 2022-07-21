## Yatube Api.
API к проекту YaTube
## Стек технологий

Python 3.9
Django 2.2.16
Django REST Framework 3.12.4
Django REST Framework simplejwt 5.1.0

## Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/anxeity/api_final_yatube.git
```

```
api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

## Примеры запросов к API:

```angular2html
GET
http://127.0.0.1:8000/api/v1/posts/
Получение списка всех постов
```

```angular2html
GET
http://127.0.0.1:8000/api/v1/posts/{post_id}/comments/
Получение списка комментариев к посту
```

```angular2html
GET
http://127.0.0.1:8000/api/v1/follow/
Получение списка подписок.
```

### Подробная информация по Api в ReDoc.
