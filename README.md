# REST_API_Yatube - API для сервиса [YaTube](https://github.com/Truth711/YaTube) .
## Возможности:

- Получение постов для любых пользователей
- Написание постов для авторизированных пользователей
- Разбиение постов на группы
- Получение и обновление с комментариев к постам
- Подписка на авторов


## Технологии:
- [Python](https://www.python.org)
- [Django](https://www.djangoproject.com/)
- [Django REST Framework](https://www.django-rest-framework.org)

## Установка и развертывание проекта:
- Клонировать репозиторий, перейти в директорию с проектом:
- Создать виртуальное окружение и установить зависимости из requirements.txt
- Выполнить команды для миграции и создания суперюзера:
```
python manage.py migrate
python manage.py createsuperuser
```
- Запустить проект:
```
python manage.py runserver
```
- Используйте следующий URL для доступа к API:
```
api/v1/
``` 
- Используйте следующий URL для ознакомления с возможностями API (URL будет автоматически доступен после запуска проекта):
```
redoc/
```
- Готово!
