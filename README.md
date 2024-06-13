# Django To-Do App

This is a To-Do application built using the Django framework for Python. The application allows users to create a to-do list by adding items, marking items as completed, deleting completed items, and deleting all items.

## Technologies Used

1. Python
3. Bootstrap
2. Django
4. JavaScript

## Additional Python Modules Required

1. Django

## Running the Project

### 1. Migrate the Database

Navigate to the project directory and run the following command to apply database migrations:

cd todo_app
python manage.py migrate


### 2. Create an Admin User

Create a superuser for accessing the Django admin interface:


python manage.py createsuperuser


### 3. Run the Development Server

Start the Django development server:


cd todo_app
python manage.py runserver


Now, you can open your web browser and go to `http://127.0.0.1:8000` to view and interact with the To-Do application.

