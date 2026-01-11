##Social Media Platform

A full-stack Social Media Platform built using Django and Django REST Framework, featuring user authentication, posts, likes, comments, friend system, and notifications. This project demonstrates real-world web application development with both backend APIs and frontend templates.

## Features

1. User Authentication (Register, Login, Logout)
2. User Profiles
3. Create, Edit, Delete Posts
4. Like &  Comment on Posts
 5.Friend Request System
 6.Notifications
 7.REST APIs with Swagger Documentation
 8.Django Templates for Frontend UI

 ##Tech Stack

Backend
Python
Django
Django REST Framework
Frontend
HTML
CSS
Bootstrap
Database
postgree 
Tools
Render
Swagger / OpenAPI
Git & GitHub

##  Project Structure
Social-Media-Platform/
│
├── accounts/        # User authentication & profiles
├── posts/           # Posts, likes, comments
├── notifications/   # Notifications logic
├── templates/       # HTML templates
├── static/          # CSS & static files
├── manage.py
└── requirements.txt

 ##Installation & Setup

Follow these steps to run the project locally:

1. Clone the repository
git clone https://github.com/Srija-Akula/Social-Media-Platform.git
cd Social-Media-Platform

2. Create virtual environment
python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate  # Mac/Linux

3. Install dependencies
pip install -r requirements.txt

4. Apply migrations
python manage.py makemigrations
python manage.py migrate

5. Create superuser
python manage.py createsuperuser

6. Run the server
python manage.py runserver


Visit  http://127.0.0.1:8000/

## API Documentation

Swagger API documentation is available at:

http://127.0.0.1:8000/swagger/

## Testing

Run tests using:

python manage.py test

## Future Enhancements

1. Profile picture & post image uploads

2. Real-time notifications (WebSockets)

3. Search users & posts

4. Responsive UI improvements

5. Deployment on Render / Railway

6. More unit & API tests

## Contributing

Contributions, issues, and feature requests are welcome!

## Contact

Srija Akula
GitHub: https://github.com/Srija-Akula
