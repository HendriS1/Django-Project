# Django-Project
## Table of Contents
1. Introduction
2. Features
3. Installing pip
4. Setting up Virtual inviroment
5. Adding Repository to Local Repository
6. Start Django app
## 1. Introduction
This is source code for my Django project.
The Goal of this project is to give a template for a starter Django
project. It gives the user the basic setup of a Django app to expand on.
## 2. Features
* SQlite3 by default
* Python Code
* Basics of Django 
## 3. Installing pip
### Unix/macOS:
Debian and most other distributions include a python-pip package. Recommend 
installing pip yourself to insure the latest version.   
python3 -m pip install --user --upgrade pip   
python3 -m pip --version
### Windows:
The Python installers for windows include pip. You can make sure that pip is 
up to date by running the following.   
py -m pip install --upgrade pip   
py -m pip --version
## 4. Setting up Virtual Inviroment
### Unix/macOS:
python3 -m pip install --user virtualenv
### Windows:
py -m pip install --user virtualenv
## 5. Adding Repository to Local Repository
Clone the repository from Github and then switch to the new Directory.   
git clone https://github.com/HendriS1/Django-Project.git   
cd Django-Project
## 6. Start Django App
### Activate the vertualenv for your project.
#### Unix/macOS:
python3 -m venv /path/to/directory
#### Windows:
py -m venv /path/to/directory
### Apply migrations for the Django app.
python manage.py migrate
### Run the Development Server
python manage.py runserver
![](Screenshots/Screenshot%202023-03-30%20011728.png)
