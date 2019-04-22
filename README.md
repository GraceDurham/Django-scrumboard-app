# Django-scrumboard-app WIP

Create a Django scrumboard app with AngularJS frontend and a Django rest-framework backend


```
Summary - Django Side
1. Installing Python 3 with Home Brew on a Mac
2. Setting up a Virtual Environment on Command Line 
3. Installing Django
4. Starting a Django Project
5. Running the Server
```

#### 1. Installing Python 3 with Home Brew on a Mac

```
Install Home Brew with 
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ brew install python3
```

#### 2. Setting up a Virtual Environment and running it on Command Line  
```
$ pip install virtualenv
$ python3 -m venv djangular
$ cd djangular
$ . bin/activate
```


#### 3. Installing Django 
```
$ pip install django

```


#### 4. Starting a Django Project
```
$ django-admin.py startproject djangular
$ cd djangular

```

#### 5. Running the server
```
$ python manage.py runserver

Copy http://127.0.0.1:8000/ and paste url in browser to see Django welcome page

```


```
Summary - Setting up Backend: Django and REST 
Creating an app, models, and a database

1. Creating a Django App
2. Adding Model Classes 
3. Running Database Migrations

```

#### 1. Creating a Django App 
```
$ python manage.py startapp scrumboard
Add 'scrumboard' under INSTALLED_APPS in settings.py in the djangular directory using your text editor and save 
It should like look this 

```


