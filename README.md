# Flask Blog API

A simple Flask-based blog application with user authentication and CRUD operations for posts.

## Features
- User Registration and Login
- Password hashing with Werkzeug
- Create, view, and manage posts
- Dashboard for logged-in users
- REST API endpoints for posts and users

## Tech Stack
- Python 3.x
- Flask
- Flask-Login
- SQLAlchemy
- SQLite (default)
- HTML/CSS for basic templates

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/<USERNAME>/<REPO>.git
   cd <REPO>
Create a virtual environment:

python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
Install dependencies:

pip install -r requirements.txt
Run the app:

python app.py
Open your browser:

http://127.0.0.1:5000
API Endpoints
POST /api/register - Register a new user

POST /api/login - Login user and get session

GET /api/posts - Get all published posts

POST /api/create - Create a post (login required)

License
MIT License


---

I can also **generate a `requirements.txt` for your project** so you can push it along with your code. This ensures anyone can run your Flask app easily.  

Do you want me to do that next?
