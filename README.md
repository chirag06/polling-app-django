# Polling Site - A Simple Django Application

> Project is developed to get started with Django framework.<br>
> A simple website that will allow people to view polls and vote.

# Installation

> Create conda environment

    conda create --name env
    conda activate env

> Clone the project and install required packages

    pip install -r requirements.txt
    git clone https://github.com/chirag06/polling-app-django.git

> Build database and indexes

    python manage.py migrate
    python manage.py makemigrations Polls
> Create a Django superuser

    python manage.py createsuperuser
> Start server

    python manage.py runserver
