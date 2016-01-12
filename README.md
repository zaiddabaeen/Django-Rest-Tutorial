# Django-REST-Tutorial
The completed Django REST Framework tutorial.

The tutorial is available at http://www.django-rest-framework.org/tutorial/quickstart/

###Versions used
Django: 1.9.1
Python: 2.7.6

###Starting up
These are the steps to initialize this project:

```
# Create a virtualenv to isolate our package dependencies locally
virtualenv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

# Install Django and Django REST framework into the virtualenv
pip install django
pip install djangorestframework
pip install pygments 

python manage.py migrate
python manage.py createsuperuser
```