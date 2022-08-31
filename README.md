# LAB-32 Django REST Framework
Base on previous lab, add auth functionality and prostgres database into the project.

## project: 
drf-api-auth-postgres
## Author: 
Rui Guo
## setup

- alias venv.
- pip install django
- pip freeze > requirements.txt
- django-admin startproject
- python manage.py migrate
- python manage.py runserver
- python manage.py startapp
- python manage.py makemigrations
- python manage.py migrate
- python manage.py creatsuperuser
- python manage.py runserver
## Docker
- docker-compose build
- docker compose up

## test

python manage.py test


