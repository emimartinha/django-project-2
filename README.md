# Django CRUD Application

## Description

This is a web application built with Django that allows users to manage tasks through a complete CRUD system (Create, Read, Update, Delete).

The application includes user authentication, task management, and a clean interface built with Bootstrap.

## Features

* User registration and authentication
* Create, update, and delete tasks
* Mark tasks as completed
* View pending and completed tasks
* Responsive UI with Bootstrap
* Clean and modular Django structure

## Technologies Used

* Python
* Django
* SQLite
* Bootstrap 5
* HTML5

## Project Structure

```
django_crud/
├── config/          # Django project settings
├── tasks/           # Main app (models, views, templates)
├── manage.py
├── pyproject.toml
├── README.md
```

## Installation

1. Clone the repository:

```
git clone https://github.com/emimartinha/django-crud-app.git
cd django-crud-app
```

2. Install dependencies (using Poetry):

```
poetry install
```

3. Run migrations:

```
poetry run python manage.py migrate
```

4. Run the development server:

```
poetry run python manage.py runserver
```

5. Open in your browser:

```
http://127.0.0.1:8000/
```

## Project Status

This project is currently under development. Deployment will be added soon.

## Author

Emiliano Martinha
