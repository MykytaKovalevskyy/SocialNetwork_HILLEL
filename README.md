# DJANGO PROJECT
## File and Folder explanation
manage.py - enables Django to locate setting.py direction
db.sqlite3 - database that will be used for Django application
Pipfile - stores needed configuration for pipenv
config/ - project directory
    __init__.py - indicates that the folder it is in will be treated as a module
    settings.py - contains Django project configuration settings
    urls.py - defines routing system
    wsgi.py - contains WSGI configuration properties
core/ - user application created via "django-admin startapp core"
    migrations/ - stores information that allows you to map the database and model definitions
    __init__.py - tells the python interpreter that the current directory will be treated as a package
    admin.py - intended for administrative functions
    apps.py - defines the configuration of the application
    models.py - stores the definition of models that describe the data used in the application
    tests.py - stores application tests
    views.py - defines functions that receive user requests, process them and return a respons
    