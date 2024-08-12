#Task Management System
This project is a simple Task Management System built with Django and Django REST Framework. It provides a RESTful API for managing tasks,and perform CRUD operations, the Django admin interface is configured to allow easy management of tasks.

Features
CRUD Operations: Perform Create, Read, Update, and Delete operations on tasks.
RESTful API: Provides endpoints for interacting with tasks via HTTP methods (GET, POST, PUT, DELETE).
Django Admin Interface: Manage tasks with a user-friendly admin panel.
Custom Admin: The admin interface is customized to display task details, search, filter, and manage related data.

installed requirement
Python 
pip (Python package installer)
Django 
Django REST Framework

API Endpoints
GET /api/tasks/: Retrieve a list of all tasks.
GET /api/tasks/<id>/: Retrieve details of a specific task by its ID.
POST /api/tasks/: Create a new task.
PUT /api/tasks/<id>/: Update an existing task.
DELETE /api/tasks/<id>/: Delete a specific task.
