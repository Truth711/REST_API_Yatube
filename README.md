<h1 align="center"> api_final</h1>
<h1 align="center"> REST API для <span style="color:red">Ya</span>tube</h1>

<h3>Автор проекта:</h3>
<h4>Truth711, студент факультета Бэкенд, когорты №47</h3> 
<h3>Как запустить проект:</h3> 

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Truth711/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```

```
source venv/Scripts/activate
```

```
python -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```

<h3>Технологии:</h3> 
<ul>
  <li>Python</li>
  <li>Django</li>
  <li>DRF</li>
</ul>