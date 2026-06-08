Farmer Mitra

Overview

Farmer Mitra is a web-based application designed to help farmers access information about government schemes and agricultural services. The platform provides secure user authentication, registration, and profile management features to improve awareness and accessibility.

Features

- User Registration
- User Login & Logout
- Password Reset Functionality
- OTP/Verification Process
- Secure Authentication System
- Farmer Profile Management
- Government Scheme Awareness
- Responsive User Interface

Technology Stack

Backend

- Python
- Django Framework

Database

- PostgreSQL

API Testing

- Postman

Version Control

- Git
- GitHub

##Project Structure
```text
Farmer_Mitra/
│
├── farmer_mitra/              # Main project settings
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
│
├── users/                     # User authentication and profile management
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── forms.py
│
├── schemes/                   # Government schemes module
│   ├── models.py
│   ├── views.py
│   └── urls.py
│
├── templates/                 # HTML templates
├── static/                    # CSS, JavaScript, Images
├── media/                     # Uploaded files
├── core_logic/                # Business logic
│
├── manage.py
├── requirements.txt
└── README.md
```
Installation

1. Clone Repository

git clone https://github.com/your-username/farmer-mitra.git
cd farmer-mitra

2. Create Virtual Environment

python -m venv venv

3. Activate Virtual Environment

venv\Scripts\activate

4. Install Dependencies

pip install -r requirements.txt

5. Configure PostgreSQL Database

Update the database settings in "settings.py".

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'farmer_mitra',
        'USER': 'postgres',
        'PASSWORD': 'your_password',
        'HOST': 'localhost',
        'PORT': '5432',
    }
}

6. Run Migrations

python manage.py makemigrations
python manage.py migrate

7. Start Server

python manage.py runserver

API Testing

Postman is used for testing APIs including:

- Registration API
- Login API
- Password Reset API
- User Profile API

Future Enhancements

- Government Scheme Recommendation System
- Multilingual Support
- Weather Information Integration
- Crop Advisory System
- AI-based Scheme Suggestions

Author

Omkar Yadav

License

This project is developed for educational and learning purposes.
