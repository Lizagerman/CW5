# CW5

## **Проект представляет собой парсер данных с площадки hh.ru**
### **Спроектированы таблицы в БД PostgreSQL и загрузка полученных данных в созданные таблицы** 

Для запуска необходимо:

* Установленный и запущенный PostgreSQL 
* Установленные зависимости проекта
* В корень проекта необходимо положить файл database.ini с параметрами для подключения к БД. По умолчанию программа подключается к базе данных 'postgres' 
* Пример содержания .ini файла:
[postgresql] host=localhost user=postgres password=12345 port=5432
* Запустить main.py
