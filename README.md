# Social Media Platform

A full-stack social media platform built using Django and Django REST Framework that allows users to connect, share posts, like, comment, and receive notifications in real time.


## Features
- User Authentication (JWT)
- User Profiles
- Create, Update & Delete Posts
- Like & Comment on Posts
- Friend Request System
- Notifications (Read / Unread)
- RESTful APIs with Swagger Documentation
- Secure API Access


## Tech Stack
- Backend: Django, Django REST Framework
- Frontend: React (Planned)
- Database: PostgreSQL / SQLite
- Authentication: JWT
- API Docs: Swagger (drf-yasg)
- Deployment: Render


## Project Structure

Social-Media-Platform/
│
├── accounts/
├── posts/
├── comments/
├── notifications/
├── social_media/
├── manage.py
├── requirements.txt
├── .env.example
└── README.md



## Installation & Setup
```bash
git clone https://github.com/Srija-Akula/Social-Media-Platform.git
cd Social-Media-Platform
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

## API Documentation

Swagger UI

## Database Design

User → Post (One-to-Many)

Post → Comment (One-to-Many)

User ↔ User (Friendship)

User → Notification (One-to-Many)

## Future Enhancements

React Frontend

Real-Time Notifications (WebSockets)

Profile Picture Upload

Rate Limiting & Security Improvements

Docker Support

Author

Srija Akula
https://github.com/Srija-Akula
