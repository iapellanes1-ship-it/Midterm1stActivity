# Django Task CRUD App

Complete Django CRUD application for managing tasks.

## Setup & Run

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

2. Make migrations:
   ```
   python crud_project/manage.py makemigrations
   python crud_project/manage.py migrate
   ```

3. Create superuser (optional):
   ```
   python crud_project/manage.py createsuperuser
   ```

4. Run server:
   ```
   python crud_project/manage.py runserver
   ```

5. Open http://127.0.0.1:8000/

## Features
- List all tasks
- View task details
- Create new task
- Update existing task
- Delete task
- Bootstrap styled UI
- Admin interface at /admin/

All required files: models.py, views.py, forms.py, urls.py implemented with class-based views.

