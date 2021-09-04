# freelance_services
После клонирования репозитория в `/config` нужно создать файл `.env`

`cp .env.template .env`

Чтобы поднять сервер нужно из корневой директории, где лежат докер файлы, выполнить команды:

`docker-compose build`

`docker-compose run --rm web python manage.py migrate`

`docker-compose up`
