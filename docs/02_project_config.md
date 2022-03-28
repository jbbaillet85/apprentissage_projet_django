# Mise en place du projet

```bash
mkdir docs
touch Readme.md
```

## Github

https://github.com/

## Wakatime

https://wakatime.com/

## Codacy

https://www.codacy.com

## Circleci

https://circleci.com/

## Python

https://www.python.org/downloads/

## Pipenv

```python
pip install pipenv
```
Sous windows:
```bash
pip install --user pipenv
mkdir .venv
touch .env
pipenv --python 3.10
pipenv install --dev flake8 pytest-django
pipenv install django
pipenv shell
pipenv run django-admin startproject config .
pipenv run django-admin startapp app_<nomApplication>
pipenv run python manage.py runserver
pipenv run pip freeze > requirements.txt
```