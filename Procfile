release: python manage.py migrate
web: gunicorn mega_zord.wsgi && celery -A celery worker -l INFO 
