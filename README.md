# recipe-app-api

Recipe app api source code

# Necessery commands:

1. sudo docker images
2. sudo docker-compose run --rm app sh -c "python manage.py startapp recipe"
3. sudo docker-compose up
4. sudo docker-compose run app sh -c "python manage.py makemigrations"
5. sudo docker-compose run app sh -c "python manage.py test && flake8"
