## Yatube Api.
### Финальный проект 9-го спринта.
### Яндекс.Практикум. 5-я когорта pythonplus.
### Студент: Андрей Федотов.
### Restapi для блога Yatube.

## Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/aafedotov/api_final_yatube.git
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
