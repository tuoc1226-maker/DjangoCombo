# Django + FastAPI

[🇯🇵 日本語](README.md) | [🇺🇸 English](README.en.md)

このプロジェクトは、FastAPIとDjangoを組み合わせ、DjangoとFastAPI両方の機能を活用できる、本番環境に対応したアプリケーションを構築することを目的としています。

その例として、サンプルブログアプリを作成しました。これは、あらゆるアプリケーションに応用可能です。

## Table of Contents:
- [Screenshots](#screenshots)
- [Tools](#tools)
- [Features](#features)
- [Installation and Usage](#installation)
- [Tutorial](#tutorial)
- [Contributing](#contributing)
- [Contact Info](#contact-info)

## Screenshots

![Django Admin Page 1](https://github.com/tuoc1226-maker/DjangoCombo/blob/main/templates/Screenshot%202021-10-23%20at%2023.12.52.png)

![Django Admin Page 2](https://github.com/tuoc1226-maker/DjangoCombo/blob/main/templates/Screenshot%202021-10-23%20at%2023.13.05.png)

![Fastapi Blog endpoints 1](https://github.com/tuoc1226-maker/DjangoCombo/blob/main/templates/Screenshot%202021-10-23%20at%2023.13.42.png)

![Fastapi Blog endpoints 2](https://github.com/tuoc1226-maker/DjangoCombo/blob/main/templates/Screenshot%202021-10-23%20at%2023.13.51.png)


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

```
bash
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

## Tutorial:

## Contributing

Pull requests and contributions are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Contact Info
If you have any question or want to reach me directly, DM . 


