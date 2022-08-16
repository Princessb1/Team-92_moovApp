release: python manage.py migrate
web: gunicorn wsgi --preload --timeout 10 --max-requests 1200
