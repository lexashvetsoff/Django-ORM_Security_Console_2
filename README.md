# Django-ORM_Security_Console
# Пульт охраны банка

Программа выводит на сайте данные о посетителях хранилища из базы данных отслеживая подозрительные посищения. 

### Как установить

Python3 должен быть уже установлен. 
Затем используйте `pip` (или `pip3`, есть есть конфликт с Python2) для установки зависимостей:
```
pip install -r requirements.txt
```

### Переменные окружения
- Создайте файл .env со следующими переменными:
```
DB_URL=postgres://USER:PASSWORD@HOST:PORT/NAME

SECRET_KEY=секретный ключ сайта

DEBUG=false (вкл/выкл режим отладки)

ALLOWED_HOSTS=.localhost,127.0.0.1,[::1],свойсайт1
```

### Запуск

```
python manage.py runserver 0.0.0.0:8000
```

### Цель проекта

Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org/).