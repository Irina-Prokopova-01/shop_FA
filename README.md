# shop_FA

Этот API предоставляет возможность управления

## Описание проекта

### Функциональные возможности
Модели данных:
* User

### API:
* Полный CRUD для моделей
* Документация API

### Тестирование:
в разработке

### Технологии
* Язык программирования: 
  Python 3.12+
* Фреймворки:
  FastAPI
* База данных: PostgreSQL 15+
* Дополнительно:

### Инструкция по запуску проекта
* Клонирование репозитория
 git clone https://github.com/Irina-Prokopova-01/shop_FA
* Установка зависимостей
 для pip: pip install -r requirements.txt
 для poetry: poetry install
* Запуск проекта
 uvicorn app.main:app --port 8000 --reload
* Доступ к документации API
  http://127.0.0.1:8001/docs#/