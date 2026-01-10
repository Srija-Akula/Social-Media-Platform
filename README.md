# Social Media Platform

A full-stack Django social media platform with authentication, posts, likes, comments, notifications, and friend system.


## Features
- User authentication (login, logout)
- Create, edit, delete posts
- Like and comment on posts
- Friend system & notifications
- REST API with Swagger documentation


## Technologies Used
- Python 3.x
- Django + Django REST Framework
- HTML, CSS (Django Templates)
- SQLite/PostgreSQL
- Swagger/OpenAPI
- Deployment: Render

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/Srija-Akula/Social-Media-Platform.git
   cd Social-Media-Platform
2. Create and activate virtual environment:

    # Windows
python -m venv venv
venv\Scripts\activate

# Mac/Linux
python3 -m venv venv
source venv/bin/activate

3. Install dependencies:

    pip install -r requirements.txt

4. Configure environment variables:

    cp .env.example .env   # Mac/Linux
    copy .env.example .env # Windows

5. Apply migrations:

    python manage.py migrate

6. Run the development server:

    python manage.py runserver

7. open in browser:

      


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
