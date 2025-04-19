# Learning Log

A web application built with Django that allows users to:
- Create an account
- Log in and out
- Create topics
- Add entries to topics
- View their learning progress

## Features
- User authentication
- CRUD operations for topics and entries
- Bootstrap 5 for responsive design
- Clean and modern UI

## Setup
1. Clone the repository
2. Create a virtual environment: `python -m venv ll_env`
3. Activate the virtual environment:
   - Windows: `ll_env\Scripts\activate`
   - Unix/MacOS: `source ll_env/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Run migrations: `python manage.py migrate`
6. Start the development server: `python manage.py runserver`

## Technologies Used
- Python 3.13
- Django 5.2
- Bootstrap 5
- SQLite3
