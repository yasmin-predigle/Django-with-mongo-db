# Django-with-mongo-db
Creating a sample project with djongo 

# Project SetUP

Create virtual environment

activate: 
  - source venv/scripts/activate

Create requirements.txt
- pip install -r requirements.txt

Create the project
- django-admin start project [project_name]

Change the settings to mongodb settings

DATABASES = {
       'default': {
           'ENGINE': 'djongo',
           'NAME': 'your-db-name',
       }
   }
- python manage.py migrate
# create models and makemigrations
- python manage.py makemigrations
- python manage.py migrate
# Create views and serializer
