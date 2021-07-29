# Django Tutorial Parts 1-4

This repository contains implementation of the parts 1 to 4 of the [Tutorial: Writing your first Django app](https://docs.djangoproject.com/en/3.2/intro/tutorial01/).


## Prerequisites

### Python

The Python version to use should be `3.6 or later`.

        $ python --version
### Django

Make sure you have `django 3.2.5` installed:

        $ python -m django --version

Otherwise after you’ve created and activated a virtual environment, enter the command:

        $ python -m pip install Django
## Quick start

1.  Clone the Project repository.

        $ git clone git@github.com:mirycantero/django-tutorial.git
        $ cd django-tutorial/mysite

2. Initialize and activate a virtualenv:

        $ python3 -m venv env
        $ source env/bin/activate

3.  Run the application:

        (env) $ python manage.py runserver

## Routes

Once you have run the application these are the routes you can play with:

- [index](http://127.0.0.1:8000/)
- [polls](http://127.0.0.1:8000/polls/)
- [admin](http://127.0.0.1:8000/admin/)
