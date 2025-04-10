# recipes-rest-api-advanced

### run linting

sudo docker-compose run --rm app sh -c "flake8"

### run tests

sudo docker-compose run --rm app sh -c "python manage.py test"
