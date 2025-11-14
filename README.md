# CMS Project

A lightweight and modular **Content Management System (CMS)** developed using Django. This project provides a clean, scalable structure suitable for building administrative systems, content dashboards, or additional CMS features. It serves as a strong foundation for further development such as user roles, authentication, content modules, and API integration.

## Features

* Built using Django 5.x
* Clean project structure with modular components
* Default admin panel enabled for managing data
* SQLite database configuration for quick setup
* ASGI and WSGI support for deployment flexibility
* Ready for extension into a full CMS platform

## Project Structure

cmsproj/
│
├── cmsproj/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│
├── manage.py
└── README.md

## Installation & Setup

1. Clone the repository
git clone https://github.com/yourusername/your-repo-name.git
cd cmsproj

2. Create a virtual environment
python -m venv env
env\Scripts\activate   # Windows

3. Install dependencies
pip install django

4. Apply migrations
python manage.py migrate

5. Run the development server
python manage.py runserver


## Your Django CMS will now be accessible at:

> http://localhost:8000

## Configuration

The project uses:

* SQLite3 database (default)
* Django’s built-in admin panel
* Default settings from settings.py
* urls.py configured with /admin/ route

You can modify settings.py to add:

* Installed apps
* Templates directory
* Static files configuration
* Database settings
* Middleware and authentication options
* Future Enhancements (Optional to Include)
* Add custom CMS modules
* Add REST API support using Django REST Framework
* Implement user roles and authentication
* Add dashboard UI (HTML/CSS/React/Angular)
* Enhance admin functionalities
* Add rich text editor for content management
* Add media upload and file management
