# ToDo app
Небольшой проект ToDo списка дел с возможность добавления новых задач и их описания через веб интерфейс или через API.
Стек: Django, Django REST Framework, Heroku, PostgreSQL.

# Установка
```
git clone https://github.com/evencatt/ToDoApp.git
```
Cоздать и активировать виртуальное окружение:
```
python3 -m venv env
source env/bin/activate
```
Установить зависимости из файла requirements.txt:
```
python3 -m pip install --upgrade pip
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

# Документация по API будет доступна по адресу:
`http://127.0.0.1:8000/swagger/`
