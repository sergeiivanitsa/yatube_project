# YATUBE
Социальная сеть для публикации дневников

Разработан по классической MVT архитктуре. Используется пагинация постов и кэширование. Регистрация реализована с верификацией данных, сменой и восстановлением пароля через email. Написаны тесты, проверяющие работу сервиса.

## Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:
```python
git clone https://github.com/sergeiivanitsa/hw05_final.git
```
```python
cd hw05_final
```
Cоздать и активировать виртуальное окружение:
```python
python3 -m venv venv
```
```python
source venv/bin/activate
```
```python
python -m pip install --upgrade pip
```
Установить зависимости из файла requirements.txt:
```python
pip install -r requirements.txt
```
Создать директории:
```python
mkdir yatube/static yatube/media yatube/sent_emails
```
Выполнить миграции:
```python
python manage.py migrate
```
Запустить проект:
```python
python manage.py runserver
```

## Стек:
* Django 2.2.16
