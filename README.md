# Описание
 API для проекта Yatube.
 ***
 ### Функционал:
 - возможность создавать посты и комментарии к ним;
 - подписываться на авторов.
 ***
 ### Порядок установки проекта:
 1.Клонируйте репозиторий к себе локально:
 - скопируйте URL-адрес репозитория
 - откройте Терминал и измените текущий рабочий каталог на расположение, где должен находиться клонированный каталог
 - введите ```git clone``` и вставьте ```URL-адрес```, скопированный ранее

2.Создать и активировать виртуальное окружение:
```
python3 -m venv venv
source venv/bin/activate
python3 -m pip install --upgrade pip
```
3. Установить зависимости из файла __requirements.txt__:
```
pip install -r requirements.txt
```
4. Выполнить миграции:
```
python3 manage.py migrate
```
5. Запустить проект:
```
python3 manage.py runserver
```
***
### Примеры:
Примеры запросов можно посмотреть по [ссылке](http://127.0.0.1:8000/redoc/) после запуска сервера с проектом.
***
### Использованные технологии:
 - [Python](https://www.python.org)
- [Django](https://www.djangoproject.com)
- [Django REST](https://www.django-rest-framework.org)
- [JWT](https://django-rest-framework-simplejwt.readthedocs.io/en/latest/)

***
###### Автор проекта 
@NikiSv