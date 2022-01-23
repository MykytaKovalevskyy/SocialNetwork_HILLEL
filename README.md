# DJANGO PROJECT
## File and Folder explanation
manage.py - enables Django to locate setting.py direction  
db.sqlite3 - database that will be used for Django application  
Pipfile - stores needed configuration for pipenv  
config/ - project directory  
&emsp; __init__.py - indicates that the folder it is in will be treated as a module  
&emsp; settings.py - contains Django project configuration settings  
&emsp; urls.py - defines routing system  
&emsp; wsgi.py - contains WSGI configuration properties  
core/ - user application created via "django-admin startapp core"  
&emsp; migrations/ - stores information that allows you to map the database and model definitions  
&emsp; __init__.py - tells the python interpreter that the current directory will be treated as a package  
&emsp; admin.py - intended for administrative functions  
&emsp; apps.py - defines the configuration of the application  
&emsp; models.py - stores the definition of models that describe the data used in the application  
&emsp; tests.py - stores application tests  
&emsp; views.py - defines functions that receive user requests, process them and return a respons  
    
