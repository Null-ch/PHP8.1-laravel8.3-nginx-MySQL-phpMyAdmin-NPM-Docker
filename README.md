<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

# Содержание
- Laravel Framework 8.83.27;
- MySQL latest;
- Nginx;
- PHPMyAdmin;
- NPM

# Установка

1. Скачать архивом либо клонировать репозиторий;
2. Запустить сборку контейнера: docker-compose up --build
3. Зайти в сам контейнер: docker exec -it project_app bash
4. Обновить зависимости: composer update
5. Сгенерировать ключ или зайти на запущенный проект: http://localhost:8076/ (или иной в зависимости от того как настроил докер и там генерировать)
5. PROFIT! Можно пользоваться

p.s. Можно установиь себе лару срашей версии, например 9: composer create-project --ignore-platform-reqs laravel/laravel:^9.0 example-app (вызываем с флагом --ignore-platform-reqs чтобы не проверял версию пхп и не выдавал ошибку)
без проверки версии пхп на твоей машине и туда добавить докер файлы папка **_docker** и **docker-compose.yml** для сборки (если работаете на другой версии лары).

Готовый для работы проект упакованный в Docker Laravel + Nginx + MySQL + PHPMyAdmin. Скачал и работаешь, без долгих настроек.
