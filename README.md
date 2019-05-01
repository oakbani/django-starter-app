# django-starter-app
Reference: https://docs.djangoproject.com/en/2.2/intro/tutorial01/

## Setup
python virtualenv <name>
source <name>/Scripts/activate
pip install requirements.txt

## Create Project and App
django-admin startproject mysite
python manage.py startapp polls
python manage.py migrate
python manage.py makemigrations polls
python manage.py sqlmigrate polls 0001
python manage.py createsuperuser

## Run development server
python manage.py runserver
python manage.py runserver 0:8000 ( 0 is shortcut for 0.0.0.0)


## To generate requirements.txt from virtual env
pip freeze > requirements.txt

