# recipes-rest-api-advanced

### run linting

sudo docker-compose run --rm app sh -c "flake8"

### run tests

sudo docker-compose run --rm app sh -c "python manage.py test"

### make migrations

🧠 Use when: You’ve changed your models and want to generate new migration files

sudo docker-compose run --rm app sh -c "python manage.py makemigrations"

### apply migrations to the database

🧠 Use when: You’ve already created migrations and want to apply them to the database.

sudo docker-compose run --rm app sh -c "python manage.py migrate"

### create super user

sudo docker-compose run --rm app sh -c "python manage.py createsuperuser"
