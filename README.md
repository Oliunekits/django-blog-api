# Django Blog / News API

**A secure REST API backend built with Django & Django REST Framework**

## Features
- Full **CRUD** operations for articles/posts
- **JWT authentication** using SimpleJWT
- Auto-generated **Swagger/OpenAPI docs**
- **Containerized with Docker**
- Ready-to-use as backend for web or mobile apps

## Tech Stack
- Python 3, Django, Django REST Framework (DRF)
- JWT (SimpleJWT), SQLite
- Docker, Swagger (drf-spectacular), GitHub version control

## Installation & Run

1. Clone project
2. Install dependencies:
```bash
pip install -r requirements.txt


## Run server 
python manage.py migrate
python manage.py runserver
