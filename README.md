# django-recipe-app-api

# created app with

`docker-compose run --rm app sh -c "django-admin startproject app .`

# running the linting tool

`docker-compose run --rm app sh -c "flake8"`

# running the api locally

`docker-compose up`

# stopping the api locally`

`docker-compose down`

# collecting static file

`docker-compose run --rm app sh -c "python manage.py collectstatic"`

# running unit tests

`docker-compose run --rm app sh -c "python manage.py test"`
