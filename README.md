# Cape Craft Projects

![Cape Craft Projects Logo](https://durbanvilledistillery.com/images/CCLogo.png)

___

## Development Flow

### Preparation

#### Environments

Enables truly deterministic builds, while easily specifying only what you want.
Generates and checks file hashes for locked dependencies.

1. Automatically install required Pythons, if pyenv is available.
2. Automatically finds your project home, recursively, by looking for a Pipfile.
3. Automatically generates a Pipfile, if one doesn't exist.
4. Automatically creates a virtualenv in a standard location.
5. Automatically adds/removes packages to a Pipfile when they are un/installed.
6. Automatically loads .env files, if they exist

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
