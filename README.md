# react_django_auth_backend

## Prerequisites:
1. Basic knowledge of Python
2. Basic knowledge of Django

## Step 1: Install dependencies
Using pipenv
``` 
pip install pipenv
pipenv install
```

Using venv
``` 
pip install -r requirements.txt
```

## Step 2: Activate Virtual Environment 
Using pipenv
``` 
pipenv shell
```

Using venv
``` 
pip install virtualenv
python<version> -m venv <virtual-environment-name>
# EG
python3.8 -m venv env

# For Mac
source env/bin/activate

# For Window
env/Scripts/activate.bat //In CMD
env/Scripts/Activate.ps1 //In Powershell
```
[Pipenv Reference](https://www.freecodecamp.org/news/how-to-setup-virtual-environments-in-python/)

[Venv Reference](https://medium.com/analytics-vidhya/python-virtual-environment-using-pipenv-22010a8bb1c2)


## Step 3 : Run the server
``` 
python manage.py runserver
```
