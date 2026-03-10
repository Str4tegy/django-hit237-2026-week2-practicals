# project_blog (Django project)

Installation and quick start

1. Create a virtual environment (Windows PowerShell):

```powershell
python -m venv .venv
.venv\Scripts\python -m pip install --upgrade pip
.venv\Scripts\python -m pip install -r requirements.txt
```

2. Initialize the database and create built-in tables:

```powershell
.venv\Scripts\python manage.py migrate
```

3. Run the development server:

```powershell
.venv\Scripts\python manage.py runserver
```

By default the site will be available at http://127.0.0.1:8000/.

Notes
- The project is named `project_blog` and contains no apps by design.
- A `requirements.xtx` file with the same dependencies is included per request.
# django-hit237-2026-week2-practicals