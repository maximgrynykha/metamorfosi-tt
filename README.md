### Предпосылки для запуска приложения (локально)  

1. Cоздайте базу данных с именем - `metamorfosi-tt` и загрузите в нее SQL-dump находящийся в корневой директории проекта.  
_**Также важно, чтобы у вас был запущен сервер СУБД.**_

2. Создание файла `.env`:
>`php -r "file_exists('.env') || copy('.env.example', '.env');"`

3. Запуск приложения:
>`php -S localhost:8000 -t public/`