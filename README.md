## Blogicum
### Платформа для блогов. Позволяет вести собственный блог и читать блоги других пользователей.

#### Стек:
Python, Django

#### Запуск отладочного сервера под windows:
В директории с проектом

#### Создание виртуального окружения:
```bash
python -m venv venv
```
#### Активация виртуального окружения:
```bash
source venv\Scripts\activate
```

Если возникла ошибка 'Имя "source" не распознано' или аналогичная:

```bash
venv\Scripts\activate
```

#### Установка зависимостей:

```bash
pip install -r requirements.txt
```
#### Запуск отладочного сервера:

```bash
cd blogicum
python manage.py runserver
```
