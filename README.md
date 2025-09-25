# CRUD FullStack: React + Django (DRF) + MySQL

## Stack
- Frontend: React + Vite (`app-contacts`)
- Backend: Django + DRF (`backend-django`)
- DB: MySQL

## Requisitos
- Python 3.10+ y pip
- Node 18+ y npm
- MySQL 8

## Cómo ejecutar

### Backend
```bash
cd backend-django
python -m venv .venv
.venv\Scripts\activate    # Windows
pip install -r requirements.txt
# Configura la BD en settings.py o .env
python manage.py migrate
python manage.py runserver
