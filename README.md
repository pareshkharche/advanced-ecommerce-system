# Multi-vendor Ecommerce System
This is a Multi-vendor Ecommerce System built using Django and ReactJS.

# Screenshots

![1](https://github.com/pareshkharche/advanced-ecommerce-system/assets/80632983/f1041328-7024-427d-a759-9f5107321531)
![2](https://github.com/pareshkharche/advanced-ecommerce-system/assets/80632983/424ce065-5604-40ea-b160-e394be4171ca)
![3](https://github.com/pareshkharche/advanced-ecommerce-system/assets/80632983/a99f45ce-c638-41e1-acd1-75d8a74edfd5)
![4](https://github.com/pareshkharche/advanced-ecommerce-system/assets/80632983/2f5e04e4-7942-4876-8237-2ad67adbfb87)
![5](https://github.com/pareshkharche/advanced-ecommerce-system/assets/80632983/992c9954-9d05-43d5-b1d7-3f7e0f56b477)
![6](https://github.com/pareshkharche/advanced-ecommerce-system/assets/80632983/7e59d06e-b42e-49e7-92fd-093330ea7f5c)
![9](https://github.com/pareshkharche/advanced-ecommerce-system/assets/80632983/92d91ba1-f5ff-44c7-8ac7-333b696a557f)
![10](https://github.com/pareshkharche/advanced-ecommerce-system/assets/80632983/2db0160d-917a-4298-b822-fac55064d0fa)
![11](https://github.com/pareshkharche/advanced-ecommerce-system/assets/80632983/dee6aada-4bd4-4485-a514-3b5b53577545)
![Screenshot (2410)](https://github.com/pareshkharche/advanced-ecommerce-system/assets/80632983/c950baf2-4aac-4c54-9bb8-049047b7e252)
![Screenshot (2414)](https://github.com/pareshkharche/advanced-ecommerce-system/assets/80632983/d3332f49-2c6f-4dcc-a1d7-3d6fa7b6f790)

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
Once the server is running, access the Django admin section by navigating to http://localhost:8000/admin in your web browser

# Notes:
Make sure to replace username/repository with the actual GitHub repository URL.
Ensure all requirements are installed before proceeding with the setup.
Follow the setup instructions carefully to avoid any errors.
