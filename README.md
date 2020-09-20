# Shopping Application product template using Django in Python 

- Step 1: Install Django

    `pip install django`
    
- Step 2: Use the CLI to setup the project:

    `django-admin startproject pyshop .`
    
- Step 3: On MacOS to start the web app:
    
    `python3 manage.py runserver`
    
- Step 4 To add new apps:

    `python3 mangae.py startapp products`

## Migrations:

- Create migrations:
    
    ` python3 manage.py makemigrations`

- Run the pending migrations:

    `python3 manage.py migrate`

## Using the admin feature:

- To create a User:

    `python3 manage.py createsuperuser`
    