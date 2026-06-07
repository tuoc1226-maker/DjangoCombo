# FastAPI and Django Combo
This projects aims to combine FastAPI and Django to build a Production ready application capable of utilizing all of the features of both django and FastAPI.
To demonstrate, I built a sample blog app, It can be adapted into any app.

## Table of Contents:
- [Screenshots](#screenshots)
- [Tools](#tools)
- [Features](#features)
- [Installation and Usage](#installation)
- [Tutorial](#tutorial)
- [Contributing](#contributing)
- [Contact Info](#contact-info)

## Tools

- Django
- Django Rest Framework (DRF)
- FastAPI
- Pydantic with custom validation
- Django all-auth
- JWT Authentication
- CORS
- Uvicorn and Gunicorn for Python web server

## Features

- CRUD endpoints for blog posts and categories
- CRUD endpoints for contacts
- Asynchronous CRUD endpoints for user accounts
- Endpoints for user authentication using DRF
- Django settings file
- Migrations using Django Migrations
- Django ORM and Admin Page
- JWT token authentication.

## Installation and Usage

Use the package manager [pip](https://pip.pypa.io/en/stable/) for installation.

```bash
- python -m venv venv
- source venv/bin/activate
- pip install -r requirements.txt
- cd fastapi-django-combo
- python manage.py makemigrations
- python manage.py migrate
- python manage.py collectstatic
- python manage.py createsuperuser
- uvicorn core.asgi:app --reload
```

## Contributing

Pull requests and contributions are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Contact Info
If you have any question or want to reach me directly, 


