# Описание
 API для проекта Yatube.
 ### Функционал:
 - возможность создавать посты и комментарии к ним;
 - подписываться на авторов.
 
 ### Порядок установки проекта:
 1. Создать и активировать виртуальное окружение:
 ```
python3 -m venv venv
source venv/bin/activate
python3 -m pip install --upgrade pip
```
2. Установить зависимости из файла requirements.txt:
```
pip install -r requirements.txt
```
3. Выполнить миграции:
```
python3 manage.py migrate
```
4. Запустить проект:
```
python3 manage.py runserver
```

### Примеры:
Примеры запросов можно посмотреть по [ссылке](http://127.0.0.1:8000/redoc/) после запуска сервера с проектом.