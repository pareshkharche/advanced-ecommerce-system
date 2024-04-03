# Multi-vendor Ecommerce System
This is a Multi-vendor Ecommerce System built using Django and ReactJS.

Demo:
https://github.com/pareshkharche/advanced-ecommerce-system/assets/80632983/f60ccdf4-e3df-4f79-a57d-29ac22961c03

This is a Multi-vendor Ecommerce System built using Django and ReactJS.

## Setup Instructions:

Follow these steps to set up the project on your local machine:

### Requirements:
- Visual Studio Code or any preferred IDE
- Python (latest version)
- Node.js (latest version)
- Git for version control

### Steps:

1. **Clone the Repository:**
   git clone https://github.com/pareshkharche/advanced-ecommerce-system

# 1.Set up Backend:

cd backend
python -m venv myenv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py runserver
python manage.py createsuperuser

# 2.Set up Frontend:

# Open a new terminal
cd frontend
npm install --global yarn
yarn create vite . --template react
yarn
yarn add axios dayjs jwt-decode js-cookie react-router-dom@6.10.0 zustand
yarn add -D simple-zustand-devtools prettier
yarn dev

# 3.Setup Django Admin:

Install Django Jazzmin
Add Jazzmin to settings.py INSTALLED_APPS section
Configure Jazzmin Settings and UI Tweaks
Create Superuser
Migrate Database
Login to the admin section


# Running the Application:
To start the Django server, run:
python manage.py runserver

# To start the frontend development server, run:
yarn dev

# Accessing Django Admin:
Once the server is running, access the Django admin section by navigating to http://localhost:8000/admin in your web browser.

# Notes:
Make sure to replace username/repository with the actual GitHub repository URL.
Ensure all requirements are installed before proceeding with the setup.
Follow the setup instructions carefully to avoid any errors.
