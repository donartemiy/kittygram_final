# kittygram
kittygram - готовый к деплою сайт по добавлению котиков с выбром цвета шерстки, года рождения и особыми навыками..

## Стек
 - python 3.9
 - django 3.2.3
 - react
 - gunicorn 20.1.0
 - nginx 1.22.1

## Проект состоит из 4х контейнеров
1. backend
   - python 3.9
   - django 3.2.3
   - gunicorn 20.1.0
2. frontend
   - react
3. gateway
   - nginx 1.22.1
4. db
   - postgres 13


## Как развернуть kittygram
1. Требуется docker v3
2. Из корня репозитория скачать:
    2.1. Файл "docker-compose.production.yml"
    2.2. Файл ".env.example"
3. Переименовать .env.example в .env
4. Рекомендуется указать собственные значения для переменных
5. Собрать контейнеры и запуститть
```bash
sudo docker compose -f docker-compose.production.yml up -d
```
6. Доступ к сайту предоставляется через порт 9000.

# Автор
- donartemiy
