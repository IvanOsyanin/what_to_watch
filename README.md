# Сервис: "Что посмотреть?"
## Выдаёт случайное мнение о фильме. 
Возможности для пользователей сайта:
- Получить случайное мнение о фильме.
- Перейти на страницу конкретного мнения по прямой ссылке.
- Добавить собственное мнение о фильме.

Каждое мнение состоит из:
- названия фильма,
- текста мнения,
- уникальной ссылки на страницу с мнением,
- ссылки на подробный обзор фильма на любом стороннем сервисе

В API имеется три эндпоинта:
- api/opinions/<id>/ — для получения, изменения или удаления отдельного объекта модели;
- api/opinions/ — для получения списка объектов и добавления нового объекта;
- api/get-random-opinion/ — для получения одного случайного объекта (мнения о фильме).

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone 
```

```
cd what_to_watch
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

```
source venv/bin/activate
```
или для пользователей Windows

```
source env/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Запустить проект:

```
flask run
```