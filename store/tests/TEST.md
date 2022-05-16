# Cape Craft Projects

![Cape Craft Projects Logo](https://durbanvilledistillery.com/images/CCLogo.png)
___

## Development Flow

### Part1

#### Getting Started

python --version
python -m venv .venv
activate
pip install django
 django-admin startproject core .
 python manage.py startapp store
settings.py - Register app
models.py
py manage.py makemigrations
py manage.py migrate

#### Configure Media Folder

#### URLs

#### Models & Admin

#### Testing Models

1. Unittest
py manage.py test
pip install coverage
coverage run manage.py test
coverage report
coverage run --omit '*/.venv/*' manage.py test
coverage html

##### Setting up a Python environment is a good idea

If you are using a windows environment, you can use pipenv to create a virtual environment.
md my project
python -m pip install pipenv 3.8.0
python -m venv ./.venv
__
Select iterpreter
__
python -m pip install django
python -m pip freeze > requirements.txt
python -m pip freeze
python -m pip install -r requirements.txt
__
Setup Django Project
__
django-admin startproject setup .

pipenv install
pipenv shell
pipenv --venv
![myGithub](https://github.com/Cape-Craft-Projects/Django/tree/Tester220514)
requirements.txt
Django>=3.0,<4.0
psycopg2>=2.8
