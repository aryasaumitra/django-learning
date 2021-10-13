# Store Front Aplication

A basic Django project with basic feature of rendering a template

## How to start a Django Projecy

```bash
django-admin startproject <projectname> .
```

## How to run a Django Project

```bash
cd projectfolder
python manage.py runserver
```

## How to add an App to Django Project

An app is basically a module in Django with it's own admin page, migrations to handle database, models, tests and views.
The Name of app needs to be appended to the projectname/settings.py in INSTALLED_APPS section
The views.py of each app is the request handler (request -> response). It also handles sending out response templates if required

```bash
django-admin startapp <appname>
```
