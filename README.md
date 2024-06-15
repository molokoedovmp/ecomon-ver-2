# Задания

1. Исправить в календаре удаление, перенос событий.
2. Уведомление событий в календаре, уведомление сообщений.
3. Сообщения - загрузка с сервера/websocket.
4. Логика записи на события. Преподаватель может указывать кол-во человек. По желанию отбор по очереди. 
5. Убрать чтобы не показывало админа.
6. Добавить отчетность для преподавателя.
7. Развернуть.
8. Отчёт, тесты(желательно Unit) и т.д

# Инструкция по запуску проекта

## Предварительные требования

Перед тем как начать, убедитесь, что у вас установлены следующие компоненты:

- [Python 3.8+](https://www.python.org/downloads/)
- [Git](https://git-scm.com/downloads)
- [Virtualenv](https://virtualenv.pypa.io/en/latest/installation.html)

## Шаги по установке и запуску

```bash
# 1. Клонирование репозитория
git clone <URL вашего репозитория>
cd <имя директории вашего проекта>

# 2. Создание виртуального окружения
python -m venv venv

# Активируйте виртуальное окружение:
# На Windows:
venv\Scripts\activate

# 3. Установка зависимостей
pip install -r requirements.txt

# 4. Применение миграций
python manage.py makemigrations
python manage.py migrate

# 5. Создание суперпользователя
python manage.py createsuperuser

# 6. Запуск сервера
python manage.py runserver

```
