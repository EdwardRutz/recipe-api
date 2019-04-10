# Build a Backend REST API with Python & Django - Advanced


- Test Stages: Setup, Execution, Assertions
- Tests require clear input and output which leads to quality code


## Tech Stack

- Python
- Pytest
- Django (ORM and Admin)
- Django REST Framework
- Docker
- Travis-CI
- Postgres


## Set-Up

- Install Django,
- Install Django REST Framework,
- Create a Django project, `django-admin.py startproject app . `
- Install Postgres,
- Flake8, `pip install flake8`
   - Create a flake8 config file in app dir
- Run tests, `python manage.py test`

## Django

- Create an app, `python manage.py startapp <appName>`
  - `python manage.py startapp core`

## Model and Database Migrations

- Create model, update settings and migrate with django
`python manage.py makemigrations core`


## Notes

- Object Relational Mapper (ORM)
- Docker will not run on Windows 10 Home but will run on Windows 10 Professional. 
  - Windows 10 home version does not have Hyper -V which Docker uses for virtualization
  


  
  
  
```  
  before_script:
  
  script: 
    - python manage.py test && flake8
```
    
## Introduction to TDD











--------------------------------------------
    
## Git

```
git add .
git commit -a
  //add message, esc, :wq
git push origin
```


## Sources

- [Udemy: Build a Backend REST API with Python & Django - Advanced](https://www.udemy.com/django-python-advanced/)
