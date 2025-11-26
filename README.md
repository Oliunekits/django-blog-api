Django Blog API

A simple Blog/News REST API built with Django, Django REST Framework, JWT authentication, and Swagger documentation.

CRUD operations

REST API architecture

Django models, serializers, views

Automatic API documentation (Swagger / OpenAPI)

Clean project structure

Good code style and best practices

Tech Stack

Python 3.11+

Django 5

Django REST Framework

SimpleJWT

drf-spectacular (Swagger docs)

SQLite (default)

Installation and Run

Clone the repository:

git clone https://github.com/YOUR_USERNAME/django-blog-api.git

cd django-blog-api

Create and activate a virtual environment:

python -m venv .venv
.venv\Scripts\activate (Windows)
source .venv/bin/activate (Linux/Mac)

Install dependencies:

pip install -r requirements.txt

Apply migrations:

python manage.py migrate

Run the development server:

python manage.py runserver

API Documentation

Swagger UI:
http://127.0.0.1:8000/api/docs/

OpenAPI schema:
http://127.0.0.1:8000/api/schema/

Blog API Endpoints

Get all articles:
GET /api/blog/articles/

Get one article:
GET /api/blog/articles/<id>/

Create article:
POST /api/blog/articles/

Update article:
PUT /api/blog/articles/<id>/

Delete article:
DELETE /api/blog/articles/<id>/

Author

oliunekits
Junior Python Developer
GitHub: https://github.com/oliunekits

License

This project is licensed under the MIT License.
