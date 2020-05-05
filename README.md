# recipe-app-api

Recipe app api source code

# Necessery commands:

1. docker images
2. docker-compose run --rm app sh -c "python manage.py startapp recipe"
3. docker-compose up
4. docker-compose run app sh -c "python manage.py makemigrations"
5. docker-compose run app sh -c "python manage.py test && flake8"
6. git commit -am "To commit in one line"
