# Jardin

## Project Overview
Jardin is a full-stack garden management app built as a solo project. It features a Django backend powered by PostgreSQL and a modern React frontend. Jardin helps users track plants, garden beds, and member contributions, serving as a showcase of independent full-stack development.

## Features
- User/member registration and authentication
- CRUD for plants and garden beds
- Task management and tracking
- PostgreSQL integration for robust data storage
- Interactive and responsive React frontend
- RESTful API between Django and React
- Admin dashboard via Django admin

## Technologies Used
- Backend: Python 3, Django, Django REST Framework
- Database: PostgreSQL
- Frontend: React, JavaScript, Bootstrap
- Other: Git/GitHub, Docker (optional for dev), CI/CD (GitHub Actions)

## Installation

### Prerequisites
- Python 3.10+
- Node.js & npm
- PostgreSQL

### Backend Setup
```bash
# Clone the repo
git clone https://github.com/thomas-hunt4/jardin.git
cd jardin

# Python virtual environment (optional)
python -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Configure your PostgreSQL database in jardin/settings.py
# Example:
# DATABASES = {
#     'default': {
#         'ENGINE': 'django.db.backends.postgresql',
#         'NAME': 'jardin_db',
#         'USER': 'your_db_user',
#         'PASSWORD': 'your_db_password',
#         'HOST': 'localhost',
#         'PORT': '5432',
#     }
# }

# Apply migrations
python manage.py migrate

# Create superuser (for admin)
python manage.py createsuperuser

# Start backend server
python manage.py runserver
```

### Frontend Setup
```bash
# In a separate terminal
cd frontend
npm install
npm start
```
The React app runs on `http://localhost:3000` and communicates with the Django backend.

## Solo Build Highlights
- Designed database schema and REST API from scratch
- Built all authentication, CRUD, and data flows independently
- Integrated PostgreSQL with Django ORM
- Developed a modern, responsive React frontend

## Screenshots
![Home Page](link-to-image)
![Admin Panel](link-to-image)
*(Replace with your own screenshots)*

## License
[MIT](LICENSE)

## Contact
Built by [Thomas Hunt](https://github.com/thomas-hunt4)
