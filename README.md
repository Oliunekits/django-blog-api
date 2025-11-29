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

- Clone project
- Install dependencies:
- bash
- pip install -r requirements.txt


## Run server  
- python manage.py migrate
- python manage.py runserver

## Open API docs (Swagger) and start testing endpoints
API Endpoints Examples:
Method	Endpoint	Description:
- GET	/articles/	List all articles
- POST	/articles/	Create article (Auth)
- PUT	/articles/<id>	Update article (Auth)
- DELETE	/articles/<id>	Delete article (Auth)

## Achievements

- Built a clean, well-structured API with secure authentication
- Created interactive API documentation
- Packaged project for easy local & Docker deployment
