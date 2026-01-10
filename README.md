# Social-Media-Platform
Social Media Platform — Django REST backend for a social media app with user authentication, posts, likes, comments, friend system, and real-time notifications.
Interactive API documentation with Swagger, clean modular design, and test coverage; ready for React frontend integration and full-stack deployment.


[![CI](https://github.com/username/Project-2/actions/workflows/django-ci.yml/badge.svg)](https://github.com/username/Project-2/actions)

## Features
- User registration/login with JWT
- Posts: create, like, comment
- Friend system & notifications
- REST API with Swagger docs
- Fully tested backend

## API Docs
Visit [Swagger UI](http://localhost:8000/swagger/) for interactive API documentation.

## Setup
1. Clone repo
2. Copy `.env.example` to `.env` and set your secrets
3. Install dependencies
pip install -r requirements.txt
4. Run migrations:
python manage.py migrate
5. Run server:
python manage.py runserver

## Testing
python manage.py test

## Future Improvements
- Add React frontend (already scaffolded)
- CI/CD deployment to Render/Heroku
- Rate limiting & security hardening

### Sample API Response
GET /api/posts/

[
  {
    "id": 12,
    "author": "srija",
    "content": "Hello world!",
    "likes_count": 5
  }
]


