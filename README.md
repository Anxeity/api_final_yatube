API проекта Yatube
Стек технологий: python, django, DRF, git, sqlite

Функционал API:
```
1) Просмотр, создание и редактирвание постов.
```
2) Просмотр групп.
```
3) Просмотр, создание и редактирвание коментариев.
```
4) Подписка на пользователей.
```

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Anxeity/api_final_yatube.git
```

```
cd kittygram
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
