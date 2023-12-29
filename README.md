# Vendor_management_system_with_performance_metrics
Designing a vendor management involves severeal steps:
**Setup django project**
Run this commands in bash/terminal
**1.Create a virtual environment**
python -m venv venv 
source venv/bin/activate  # On Windows, use "venv\Scripts\activate"
**2.Install django and rest framework**
pip install django djangorestframework
**3.Create a new Django project**
django-admin startproject vendor_management_system
**4.Move to the project directory**
cd vendor_management_system
**Create a new app for vendors**
python manage.py startapp vendors

Extract the zip file and run it.

**Apply migrations to create database tables**
python manage.py makemigrations
python manage.py migrate

**Run the python file using the command **
python manage.py runserver

**Create a new vendor**: POST /api/vendors/
**List all vendors**: GET /api/vendors/
**Retrieve a specific vendor's details**: GET /api/vendors/{vendor_id}/
**Update a vendor's details**: PUT /api/vendors/{vendor_id}/
**Delete a vendor**: DELETE /api/vendors/{vendor_id}/
**Retrieve a vendor's performance metrics**: GET /api/vendors/{vendor_id}/performance





