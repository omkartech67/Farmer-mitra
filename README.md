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

Project Structure

Farmer_Mitra/
│
├── core_logic/
├── templates/
├── static/
├── media/
├── users/
├── schemes/
├── manage.py
└── requirements.txt

Installation

1. Clone Repository

git clone https://github.com/your-username/farmer-mitra.git
cd farmer-mitra

2. Create Virtual Environment

python -m venv venv

3. Activate Virtual Environment

Windows:

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
